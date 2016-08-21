# test
Purpose
To create a SAS data set from raw data, you must examine the data records first to
determine how the data values that you want to read are arranged. Then you can look
at the styles of reading input that are available in the INPUT statement. SAS provides
three basic input styles:

list

column

formatted
You can use these styles individually, in combination with each other, or in conjunction
with various line-hold specifiers, line-pointer controls, and column-pointer controls.
This section demonstrates various ways of using the INPUT statement to turn your raw
data into SAS data sets.
You can enter the data directly in a DATA step or use an existing file of raw data. If
your data is machine readable, then you need to learn how to use those tools that
enable SAS to read them. If your data is not yet entered, then you can choose the input
style that enables you to enter the data most easily.
Prerequisites
You should understand the concepts presented in Chapter 1, “What Is the SAS
System?,” on page 3 and Chapter 2, “Introduction to DATA Step Processing,” on page 19
before continuing.
