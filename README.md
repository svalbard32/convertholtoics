# convertholtoics
Instructions on converting .hol to .ics. This allows you to create holiday calendars for Outlook.

**Steps (tested on Windows):**
1. Manually update .hol file to have your holidays. if you don't have one, an example one is uploaded here: https://github.com/svalbard32/convertholtoics/blob/main/Example%202025%20Holidays.hol
2. (if necessary) Convert from UTF-16 to UTF-8. A tool you can use is: https://www.tbxconvert.gevterm.net/cgi-bin/utf16-utf8.cgi
3. Rename output file to sti.hol
4. Install Ruby: https://www.ruby-lang.org/en/documentation/installation/
5. Download hol2ics from here https://github.com/erwdavid/hol2ics and unzip to your Ruby folder.
6. Run Start Command Prompt with Ruby.
7. Run cd "your ruby folder location\hol2ics-master" in there.
8. Run ruby hol2ics.rb sti.hol in there.

**Installing the calendar:**

_Outlook Windows (installed):_
1. Open the .ics file.
2. If a box that pops up asking "Do you want to open this calendar as a new calendar or import its items into your calendar," click Import.
3. If Step 2 doesn't occur, a window will pop up in Outlook. Check the box next to the name of the holiday calendar you want to add and click OK.

_Outlook Mac (installed):_
1.	In Outlook for Mac, at the bottom of the navigation pane, find Calendar.
2.	In Finder, locate the .ics file, and drag the .ics file to the Outlook Calendar grid or list.
3.	Click on Import in the Add Event menu.

_Outlook Web:_
1.	Go here: https://outlook.office.com/calendar/addcalendar
2.	Click on the Upload from file section, click “Browse” then find the file where you saved it on your computer and click Import.
![Outlook Web Upload](https://github.com/user-attachments/assets/3c3eab0b-00be-4ad8-ab9f-75afb386ffce)
