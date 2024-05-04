# uiview-plus
Extending UIView to make boilerplate layout easier

### Example usage

```
func addContentView() {
  let sideMargin: CGFloat = 30
  let verticalMargin: CGFloat = 50
  view.addSubview(contentView)
  contentView.pinLeadingToParent(margin: sideMargin)
  contentView.pinTrailingToParent(margin: sideMargin)
  contentView.pinTopToParent(margin: verticalMargin)
  contentView.pinBottomToParent(margin: verticalMargin)
  contentView.backgroundColor = .systemBackground
  contentView.roundCorner(radius: 16, cornerCurve: .continuous)
}
  
```
