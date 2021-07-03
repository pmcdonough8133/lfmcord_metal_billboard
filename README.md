# Last.fmcord #metal Billboard


# Instructions
1. Run the "billboard.exe" file
2. On the command prompt that opens, you will receive a few prompts, you can hit enter for the first two without worry (if this is a weekly report, for monthly or other, follow the second prompt)
3. On the third prompt regarding friend's list or usernames, paste the list of names from settings.txt into the command line and hit enter (ignore IAmThBlackMetal as that is on a separate line, I am hardcoded in which is the first prompt)
4. The last prompt is asking about which type of data do you want, artist, album, or track.  The default is album so you can just hit enter for that.  For artist, type a and hit enter.
5. The script will run and show current progress, once it completes, a "billboard.csv" file will appear in the directory you ran the "billboard.exe" file from.
6. Open a new Excel doc, click the data tab and choose the option to get data from text/csv.  This will open a window asking about import file, navigate to where your "billboard.csv" is located and select it.
7. A window inside Excel will open asking you to choose formats for the import, under the "File Origin" dropdown menu, select "65001: Unicode (UTF-8)" and leave the other options as default (should Comma for Delimiter and First 200 Rows for Data Type Detection). Click Load at the bottom right.
8. Copy the Columns containing the data (you don't need the rank column, usually called Column 1)
9. Got to Google Sheets for the Billboard and paste (try ctrl+shift+v to avoid pasting the color formatting) the copied data into the area for the new billboard. I'll take care of the google sheets side of things so I'll already have the area ready for you and I can handle all the formatting and whatnot once it is pasted.
10. Repeat from step 1. for either artist or album depending on which one you did first
