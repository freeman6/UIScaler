# UI Scaler

A Windows Forms automatic UI scaler for C#! It is very easy to use, simply load the form you want, and after it is rendered just call `UIScaler.AddToScaler`, similar to this:

```
protected override void OnShown(EventArgs e) {
	base.OnShown(e);
	UIScaler.AddToScaler(this);
}```

An you're done!

![Alt Text](https://media.giphy.com/media/k7NrrrPBLsHdGBsDUR/giphy.gif)

Of course, there are methods found in the UIScaler class that allow you to further customize the appearance, such as excluding some controls from scaling. Any controls that are added or removed from the form and child controls are managed automatically, so no need to worry about managing references or child control scaling. :)
