# excel helper files
File "Copy only rows with data.xlsm" contains a macro that will combine multiple workssheets in a spreadsheet into one single sheet. This is helpful if your data has the same column headers but is split up into multiple sheets for whatever reason. The macro will only copy cells from sheets in the current spreadsheet with data and will ignore empty cells. This will also copy the column headers from every sheet, so you may need to clean that out of your merged data. Note: This only copies data from existing sheets in the spreadsheet, it does not contain any prompts to add separate spreadsheets.

File "CopyRangeFromMultiWorksheets().txt" is the plain text of the macro.

Make sure to have Developer ribbon showing in Excel so you can use macros (Options -> Customize Ribbon -> Check the Developer box). Once you have all of your sheets compiled into one spreadsheet, select the Macros button under the Developer tooltab, select the macro, and then click Run.

I wish I could find the original macro that I edited for my purposes to credit the author.
