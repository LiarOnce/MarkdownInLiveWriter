MarkdownInLiveWriter
====================

This project is a markdown plugin for [Open Live Writer](http://openlivewriter.org). 

You can use this plugin to write your blog in markdown, and it provides the live preview and code syntax highlight.

It built from [fresky/MarkdownInLiveWriter](https://github.com/fresky/MarkdownInLiveWriter)

## Have a bug in Open Live Writer 0.6.2.0!

```
发生意外错误
应用程序发生意外错误。

System.NullReferenceException: Object reference not set to an instance of an object.
   at MarkdownInLiveWriter.MarkdownForm.highlightCode()
   at MarkdownInLiveWriter.MarkdownForm.highlightBtn_Click(Object sender, EventArgs e)
   at System.Windows.Forms.Control.OnClick(EventArgs e)
   at System.Windows.Forms.Button.OnClick(EventArgs e)
   at System.Windows.Forms.Button.OnMouseUp(MouseEventArgs mevent)
   at System.Windows.Forms.Control.WmMouseUp(Message& m, MouseButtons button, Int32 clicks)
   at System.Windows.Forms.Control.WndProc(Message& m)
   at System.Windows.Forms.ButtonBase.WndProc(Message& m)
   at System.Windows.Forms.Button.WndProc(Message& m)
   at System.Windows.Forms.Control.ControlNativeWindow.OnMessage(Message& m)
   at System.Windows.Forms.Control.ControlNativeWindow.WndProc(Message& m)
   at System.Windows.Forms.NativeWindow.Callback(IntPtr hWnd, Int32 msg, IntPtr wparam, IntPtr lparam)
```
I am not a professional C # programmer, so I do not know how this bug should be fixed, if you know how to repair please initiate a Pull request.

## Installation

**Option 1:**

Download the [MarkdownInLiveWriter.dll](https://github.com/LiarOnce/MarkdownInLiveWriter/raw/master/MarkdownInLiveWriter.dll), 
then put it in the [OpenLiveWriterPath]\Plugins\.

## Screenshot

![screenshot](https://ooo.0o0.ooo/2017/02/25/58b11c88ef3fb.png)

## Requirements

Please install [Open Live Writer](http://openlivewriter.org) and .NET Framework 4.5.2 and later.

## Credits

This project is using [markdownsharp](http://code.google.com/p/markdownsharp/), which is a open source C# implementation of Markdown processor.

## License

MarkdownInLiveWriter is released under the MIT License. See the bundled LICENSE file for details.

## Chang Log
1. 02/25/2017	build the Open Live Writer ver. and delete the wix installer file
1. 08/01/2013	add the wix installer file
1. 07/19/2013	support code syntax highlight
1. 07/16/2013	initial version
