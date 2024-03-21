/*
 * Copyright (C) 2020 Nawdeep Goyal.
 *
 * These coded instructions, statements, software and computer programs contain
 * unpublished proprietary information of Nawdeep Goyal(nawdeep9@gmail.com), and are
 * copy protected by law. They may not be disclosed to third parties
 * or copied or duplicated in any form, in whole or in part, without
 * the specific, prior written permission of Nawdeep Goyal.
 * Unauthorised usage of this software may lead to copyright claims.
 */


Software Requirnments:
1) Java 1.8 and above must be installed in your system.
2) Windows operating system.

Steps to Install:
1) Copy the reconciliation.zip in a folder
2) Right click -> Unzip here
3) Open rereconciliation folder
4) Double click on register.bat 


How to run: 
1) Right click on run.bat -> edit -> Put path of your folder or full path of your excel file after ./convertor-1.0-jar-with-dependencies.jar 
  	Note That there will be single space between jar file and path of your excel.
2) Double click on run.bat everytime you want to create your reconciliation sheet.

you can always do the above 2 steps whenever you want to change the location of your excel file.
Please note that you can put either full path of your single excel sheet or you can give path of your folder where you have kept multiple excel sheets.
in case you choose to put folder path, it will autoamtically create reconciliation sheets for all the excel files present in that folder.

3) Additionally you can also create desktop shortcut of run.bat and run this instead.

Note that you can either choose to use Excel.xlsx as a template to create all your reconciliation sheets or you can make your own excel file the way you like but make sure you make the corresponding changes of column no. in excel_config.properties file present inside software folder.