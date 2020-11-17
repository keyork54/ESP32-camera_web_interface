# camera_web_interface
## Utility software to convert *.h files in ESP32-Cam software to HTML files for editing then convert those HTML files back to compatible *.h files.

This is intended for *camera_index.h* and assumes that it and 7z.exe are in the same folder as *ConvertHtoHTML.exe* and *ConvertHTMLtoH.exe*.

If you want to convert another file, type it's name on the command line. Regardess of the name provided *ConvertHTMLtoH.exe* will always create *camera_index.h*. You may rename the file afterwards.

This software is written in C# and requires .Net to be installed on the development machine before it will run.
