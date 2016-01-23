# TimeSinceTextView
This is a subclass of android.widget.TextView which exposes a method `setDate()` which can take either a Unix timestamp (`long`) or `java.util.Date`. The view converts the date into a String which describes the date in terms of time since.

e.g. If the current timestamp is Unix 1453503166 and the time passed to `setDate()` is 1453503116, "50 seconds ago" is displayed.

## Screenshot
![Screenshot](/screenshots/1453502946.png)

## Contributions

Pull requests are welcome, in particular in would be nice to have [strings.xml](timesincetextview/src/main/res/values/strings.xml) translated into as many languages as possible.