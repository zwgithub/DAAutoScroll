## DAAutoScroll

DAAutoScroll is a collection of UIScrollView subclasses that allows a UIScrollView (or similar) to automatically scroll itself with adjustable speed. When the user interacts with the view, the scrolling automatically stops.

View the included example project for a demonstration.

## Installation

To use DAAutoScroll:

1 - Copy over the `DAAutoScroll` folder to your project folder.
2 - Subclass.
Optional - Customize.

## Usage
Wherever you want to use DAAutoScroll, import the appropriate header file and subclass as follows:

For UIScrollView:
```
' #import "DAAutoScrollView.h" '
```

For UITableView:
```
' #import "DAAutoTableView.h" '
```

For UITextView:
```
' #import "DAAutoTextView.h" '
```

Subclass either via code or Interface Builder.

To restart scrolling after user interaction, you need to support the UIScrollView delegate methods 'scrollViewDidEndDragging:' and 'scrollViewDidEndDecelerating:', and call `startScrolling` again. The example does this by default.

### Automatic Reference Counting (ARC) support
DAAutoScroll was made with ARC enabled by default.

## Contact

- [Personal website](http://www.amitay.us)
- [GitHub](http://github.com/danielamitay)
- [Twitter](http://twitter.com/danielamitay)
- [LinkedIn](http://www.linkedin.com/in/danielamitay)
- [Hacker News](http://news.ycombinator.com/user?id=danielamitay)
- [Email](daniel@amitay.us)

If you use/enjoy DAAutoScroll, let me know!

## License

### MIT License

Copyright (c) 2012 Daniel Amitay (http://www.amitay.us)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
