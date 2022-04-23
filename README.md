# play-reader
Simple reader app for [play.date](https://play.date).  
Readable text files: `.txt`, `.md`, `.adoc`, `.rst`.  
Currently it can access app folder or app data folder, so to add new book you'll need to add it in `Source` folder, and then [re-compile project](https://sdk.play.date/1.10.0/Inside%20Playdate.html#_compiling_a_project) (`pdc play-reader/Source`).

![example](./example.gif)

# How-to use
Initial screen shows list of readable files.  
Button A opens selected file. Scrollable via d-pad or crank.  
Button B returns to files list.  