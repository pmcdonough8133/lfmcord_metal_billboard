# Last.fmcord #metal Billboard


# Instructions
1. Run the "billboard.exe" file
2. On the command prompt that opens, you will receive a few prompts. For the first, enter your username. NOTE: whoever takes over will want to remove their name from the settings list or make sure to skip themselves using the second prompt. If you removed yourself from the settings list, you can hit enter for the second without worry.
3. The third prompt asks about timeframe, weekly is default so you can just hit enter most times (for monthly or other, follow the instructions).
5. On the fourth prompt regarding friend's list or usernames, paste the list of names from settings.txt into the command line and hit enter.
6. The last prompt is asking about which type of data do you want, artist, album, or track.  The default is album so you can just hit enter for that.  For artist, type a and hit enter. (I never implemented track so... sorry)
7. The script will run and show current progress, once it completes, a "billboard_datatype.csv" file will appear in the directory you ran the "billboard.exe" file from.
**For Excel!!**
8. Open a new Excel doc, click the data tab and choose the option to get data from text/csv.  This will open a window asking about import file, navigate to where your "billboard.csv" is located and select it.
9. A window inside Excel will open asking you to choose formats for the import, under the "File Origin" dropdown menu, select "65001: Unicode (UTF-8)" and leave the other options as default (should Comma for Delimiter and First 200 Rows for Data Type Detection). Click Load at the bottom right.
10. Copy the Columns containing the data (you don't need the rank column, usually called Column 1)
**For Google Sheets!!**
11. I like to use an import sheet in which you use the "Import" function under the File menu. Choose upload and drag the csv to the drop spot. Choose to replace current sheet.
**Continue from the excel or google sheet section**
12. Go to Google Sheets for the Billboard and paste (try ctrl+shift+v to avoid pasting the color formatting or anything else weird) the copied data into the area for the new billboard.
13. Repeat from step 1. for either artist or album depending on which one you did first
