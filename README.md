# JS3DTouchTableViewController
An easy way to add Peek and Pop to UITableViewController

Just use this as your superclass instead of UITableViewController and implement the `tableView(tableView:, peekViewControllerForRowAt:)` method:
```swift
class MyCustomTableViewController: JS3DTouchTableViewController {
...

  override func tableView(_ tableView: UITableView, peekViewControllerForRowAt indexPath: IndexPath) -> UIViewController? {
    return someViewController
  }
}
```
