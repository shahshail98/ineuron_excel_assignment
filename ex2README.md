# ineuron_excel_assignment
# What do you mean by “Relative Cell Referencing” in MS Excel and “Absolute cell referencing”?
There are two types of cell references: relative and absolute. Relative and absolute references behave differently when copied and filled to other cells.
Relative references change when a formula is copied to another cell. Absolute references, on the other hand, remain constant no matter where they are copied.

# How to secure an excel workbook, demonstrate it with an example.
1) “Mark As Final” Excel option is used for Protecting Excel File From Editing by another user. It’s like a reminder more than protecting Excel by turning OFF the typing-editing commands.

One can easily identify that the Excel file is protected from editing by seeing the marked as final icon which appears on the status bar.

Steps to apply Mark As Final for protecting Excel File from editing:
Just open the Excel file in which you want to apply this mark as final option.
Tap to the following: file > Info > Protect Workbook > Mark as Final options.
![image](https://user-images.githubusercontent.com/88320437/155884380-ba57fd00-c1f2-4b5c-9065-9f21ca78dbd2.png)
Hit the ok button to save and apply the changes.
2) If you want to protect the complete of your workbook from editing then you have two options to perform.

Encrypting your Excel Workbook with the Password
Making your workbook read-only
1.  Encrypt Excel Workbook With A Password
To protect Excel Workbook from editing the very first option is to encrypt the workbook with some password.

So that whenever anyone else tries to open your Excel workbook, firstly they need to enter the password.

Note: try you need to set some tough Password that no one can guess.

Steps to encrypt Excel workbook with a password:

Open your Excel file and click on the following options: File>info>Protect Workbook.
From the Protect Workbook drop-down options choose the “Encrypt with Password”.
![image](https://user-images.githubusercontent.com/88320437/155884456-a30a0da9-fc98-4f82-b791-5252ce0f57aa.png)
In the opened window of Encrypt Document, just enter the password which you want to set. After that click to the ok.
![image](https://user-images.githubusercontent.com/88320437/155884469-40471f82-3f5c-4fbc-93f8-6d2f14927a58.png)
For the password confirmation, you are asked to enter the password two times. After that click the OK button.
![image](https://user-images.githubusercontent.com/88320437/155884484-f9cd8785-40cc-49b5-969f-8835b00f35a0.png)
To check whether your Excel workbook gets encrypted properly or not, You need to close your already opened workbook and re-open it again.
![image](https://user-images.githubusercontent.com/88320437/155884508-1b3feb98-60ff-497d-afa6-9b61af08be79.png)
Make A Workbook Read-Only
Making Excel workbook read-only is very easy. This option doesn’t give any real protection so any user who is opening the file can easily enable the editing option. But it will give suggestions to the other user for being careful while making changes in the file.

At first, Open your Excel workbook which you want to make read-only.
Now Go to the file > info> Protect Workbook.
Now from the drop-down options of Protect Workbook choose the “always open read only”.
![image](https://user-images.githubusercontent.com/88320437/155884603-ce044a28-de44-40f8-8e12-30964c2ca56d.png)
After applying this, whenever anyone tries to open the Excel file, they will get the warning that the file is opened in read-only mode.
For removing up this read-only setting, just go to the File > Protect Workbook Now toggle the “Always Open Read-Only” setting off.

# Explain the pivot tables and their implementations.
A Pivot Table is one of the basic data analysis tools. Pivot Tables can quickly answer many important business questions.
One of the reasons we build Pivot Tables is to pass information. We would like to support our story with data that is easy to understand, easy to see. 
Although Pivot Tables are only tables and thus missing real visuals, they can still be considered as a mean of Visual Storytelling.
![image](https://user-images.githubusercontent.com/88320437/155884782-4804cc15-e5fb-4eb6-af29-bfe08a739361.png)

# Explain lookup in excel with suitable examples.
LOOKUP(lookup_value, array)
=LOOKUP(B2,D2:F5)
![image](https://user-images.githubusercontent.com/88320437/155884905-f9d8ea6a-d496-4b13-b1a0-44acf302080f.png)

# What is Data validation, and how to implement it in Excel?

xcel Data Validation is a feature that restricts (validates) user input to a worksheet. Technically, you create a validation rule that controls what kind of data can be entered into a certain cell.

Here are just a few examples of what Excel's data validation can do:

Allow only numeric or text values in a cell.
Allow only numbers within a specified range.
Allow data entries of a specific length.
Restrict dates and times outside a given range.
Restrict entries to a selection from a drop-down list.
Validate an entry based on another cell.
Show an input message when the user selects a cell.
Show a warning message when incorrect data has been entered.
Find incorrect entries in validated cells.
For instance, you can set up a rule that limits data entry to 4-digit numbers between 1000 and 9999. If the user types something different, Excel will show an error alert explaining what they have done wrong:
Data Validation in Excel
![image](https://user-images.githubusercontent.com/88320437/155885391-075d0bc1-6c48-4b8a-af12-348858bc928d.png)




