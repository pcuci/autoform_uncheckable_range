# Uncheckable Radios Autoform Field
Ever wanted to uncheck a range slider inside a form? I mean really undo, as in un-select, de-select, un-check the element as if it was never selected

Now you can!

### Note
Field must be `optional: true` - obviously!

```coffeescript
Topics.attachSchema new SimpleSchema(
  feelingGood:
    type: String
    label: "Good"
    optional: true
    autoform:
      type: "uncheckable-range"
```
