# Contributing

Although this is a public repository, unless you are directly added as a contributor, there's no way for you to edit it. However if you are added as a contributor, there are a few basic things you should know about contributing to this repository.

## Project Structure

This project is structured as follows:

```
+-- README.md
+-- assets
|   +-- images
|   |   +-- [various images]
|   +-- videos
|   |   +-- [various videos]
+-- dist
|   |   +-- README.pdf
+-- .vscode
|   |   +-- settings.json
|   |   +-- extensions.json
```

The **README** file is where the actual quickstart lives. Any assets (images or videos) used inside the **README** live inside respective /**images** and /**videos** subdirectories of the /**assets** directory. The /**dist** directory holds all of the various distributable verisons of the **README** which in other words are in different file formats that may be more easily accessible than the Markdown version.

## Software Requirements

In order to contribute to this repository, you don't need any special software beyond a text editor – however, Visual Studio Code is strongly recommended as the main text editor for reasons which you will see shortly.

## Converting Markdown into a PDF

Because the main distributable version of the README is in PDF format, where as the source version is in Markdown, there needs to be a way to convert between both. Although there are many online conversion tools, the easiest way to do so is in Visual Studio Code with the [Markdown PDF extension](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf), which is why Visual Studio Code is the recommended editor. There's already a **.vscode** folder inside this project configuring the extension as necessary, so as soon as you open up this workspace, you'll be prompted to install it. You can then open up the README, followed by opening up the command pallate with "`Cmd + Shift + P`" or "`Ctrl + Shift + P`". Then type in "_Markdown PDF: Export (pdf)_" and hit enter.

> **Note:** You'll only be able to see the "_Markdown PDF: Export (pdf)_" command inside the command palatte if you opened the command palatte while having the **README** file open. If you don't see it, try it again making sure that the README is the current active file in Visual Studio Code.

It should automatically then generate a **README.pdf** in the **dist** directory based on the main **README**.

> **Note:** This is not the default setting of the extension, rather it is one that was configured inside the **settings.json** file inside the **.vscode** folder.

## Making Changes

Since there's nothing too complicated going on with this repository and only invited contributors are allowed to make changes, making edits to files in the GitHub repo is as simple as making commits and then pushing it back to GitHub.
