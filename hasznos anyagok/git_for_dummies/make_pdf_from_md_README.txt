To make a pdf file from a markdown (.md) file, do one of the following:

Download VS Code's Markdown Converter extension. Open your .md file in VS Code.
Hit ctrl+shift+p, type convert. The Markdown: Convert document command will show up.
Hit enter. The PDF will be created in the same directory as your .md file.
If you don't have Chromium installed, then VS Code will prompt you to install it when you first run
this command. Click on install to install it, so you can use this extension.

The second version to make a pdf is with pandoc. If you have pandoc installed, execute the following command:

pandoc -s -o your_file.pdf your_file.md