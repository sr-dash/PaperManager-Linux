# PaperManager-Linux
A standalone Ubuntu application for viewing, tagging and managing research papers. App is based on PyQt6.

# Install instructions

Type the following command in a local terminal for installing the app. 

```
git clone https://github.com/sr-dash/PaperManager-Linux.git
cd PaperManager-Linux
sudo dpkg -i PaperManager_deb.deb
```

If there are any issues clonning the repository, you can try pulling the binary file from the release as,
```
https://github.com/sr-dash/PaperManager-Linux/releases/download/v1.0.0/PaperManager_deb.deb
```
and then install as 
```
sudo dpkg -i PaperManager_deb.deb
```
Here is a sample screenshot of the UI within aa Ubuntu installation.
![App_Preview](Sample_UI.png)

The app creates local directories for storing the pdf file sof the papers and related tags (database).

Hope you find the app helpful. 

Create issues or PRs here for reporting bugs/issues or suggesting further developments.

