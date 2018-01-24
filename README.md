# FixMissingMSI Version 2.0

FixMissingMSI is a tool to fix missing/mismatched MSI/MSP files in widnows installer cache folder, especially for SQL product this tool extends the capability of “FindSQLInstalls.vbs script” from below article:
https://support.microsoft.com/en-us/help/969052

This tool has a friendly user interface to tell you what setup related MSI/MSP files are missing or mismatched in cached directory c:\windows\installer. It enables you recover the missing/corrupt/mismatched cached MSI/MSP files of products by one click. You can also get detailed information about the cached MSI/MSP files in the tool report. If you download service pack or CU from website you need to use X option to extract the downloaded package to extract those MSI/MSP files to the folder, to feed the tool for MSI/MSP meta data. Detailed readme please see the readme document inside the FixMissingMSI folder.

I would recommend you  use Windows Installer Cache Verifier Package, as directed in KB article 2667628, to verify the cached  MSI/MSP files if you use this tool to fix MSI/MSP files.

The binaries can be downloaded in Release tab or below:
https://github.com/suyouquan/SQLSetupTools/releases/download/V2.0/FixMissingMSI_V2.0.zip

Note that you need NET 4.5 to run above version.
If you don't have .NET 4.5 installed please download older version that support .NET 3.5 in release tab of this website.

Screenshot:
![screenshot](https://user-images.githubusercontent.com/35096859/35314819-939ae972-0103-11e8-8e32-f0f9bcc7475e.png)
