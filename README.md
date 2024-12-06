# Xeno-SRC
Archived because I knew it would get deleted soon

I did NOT make this, all credit goes to .rizve, this is only an archive of the files if they get deleted.

# Fixing Issues
Incompatible Command-Line Options: '/O2' and '/RTC1'
Solution:

1. Go to the top menu and click Project > Xeno Properties. (Dont forget to select Xeno on the solution explorer)
2. Expand the C/C++ section in the side menu.
3. Select Optimization.
4. Change the Optimization setting to Disabled (/Od) using the dropdown menu.

Wrong version error
Solution:

1. Download ClientsWindow.xaml.cs from the repo.
2. Replace the old ClientsWindow.xaml.cs (Main Folder > XenoUI > ClientsWindow.xaml.cs) with the downloaded one.

# Making your own UI
1. **Open the Solution Explorer**  
   - Find "XenoUI" in the Solution Explorer pane.  
   - Open **`MainWindow.xaml`**.  

2. **Editing the Menu**  
   - Once the file is open, you can start customizing the UI.  

3. **Editing Additional Windows**  
   - **ClientsWindows.xaml**:  
     - This file is for enabling the multi client feature UI.  
     - Double-click on **`ClientsWindows.xaml`** in the Solution Explorer to open it for editing.  

   - **ScriptsWindow.xaml**:  
     - This is the main window.  

# Updating offsets
Go to the file: 
Main Folder > Xeno > include > worker.hpp
