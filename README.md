Welcome To MechTools!

A desktop application aiming to assist in your design process

Available features:

Calculation
- Thread Stress
- Fastener Elongation
- Fastener Quantity
- Hole and Shaft fits
- ISO268-2 Tolerances

~~~ Versioning ~~~
The Version System is a semantic 3 part number

Major.Minor.Patch

It is recommended a user always uses the latest version

When a new version is release MechTools will prompt the user and help them download the newer one
and view the changelog


~~~ Bug Reports & Feature Requests~~~
Feedback to the developer can be given directly or via the forms in the window or links below
Please provide as much information as possible and attach or copy the details from your crashlog if relevant

Bug reports can be submitted via the option under Edit
or directly via:

https://gitreports.com/issue/EngineeringDeveloper/MechToolsDev
OR
https://github.com/EngineeringDeveloper/MechTools/issues

Feature request can be submitted via the option under Edit
or directly via:

https://gitreports.com/issue/EngineeringDeveloper/MechTools
OR
https://github.com/EngineeringDeveloper/MechTools/issues


~~~ User Data ~~~

The users data is theirs to modify and control
It is generally stored in %AppData%/Roaming/EngineeringDeveloper/MechTools for windows

you can access this folder easily by in the Edit -> Preferences -> DataFiles

The Data folder contains data used within the program like:
fastener information and material options.
If you wish you add more options to your datafiles you can edit these files manually.
If you think your additions will be usefull for other users, you can also submit a feature request under Edit -> Feature Request


~~~ Editing the Datafiles ~~~
the datafiles are all tab delimited ie
"data"\t"moredata"
The first row is reserved for the titles of each column

it is required that all columns are filled in for each row
if you wish to enter no data you can provide a value of 0.0, but it is recomended to provide all the data

The simplest way to prevent errors is to copy a similar row and change the values.

------------------------------

~~~ Settings ~~~
Settings.txt can be modified manually by changing settings between "true" and "false"
but it is better to modify these via the Preferences window

if you ever have an unrecoverable crash after editing the Datafiles it is likely that the format you edited them to is invalid
you can reset your files by changing the first_start value in the settings.txt to first_start=true, or deleting your MechTools folder in appdata.

----------------

~~~ Tooltips ~~~

Tooltips have been added where relevant
hovering over an entry or menu item will show a tooltip with some context information


~~~ IN DEV Features ~~~

Features which are planned have been indicated by greyed out menuoptions
If you hover over an indev option a tooltip will pop up with more information on what it will become

If you feel a feature will become useful soon then you can let the developer know via a Feature Request!

