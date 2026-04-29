# A Comparison of Data Sanitization Methods
## Objective
The objective of this project is to demonstrate the effectiveness of various **data Sanitization** methods. 

Deleted files will be inspected for artifacts using third party tools such as [Eric Zimmerman Tools](https://ericzimmerman.github.io/#!index.md) as well as built in tools such as Windows' Registry Editor.

## File Deletion
File deletion will replicate common user deletion methods e.g. right clicking and sending to the Recycle Bin. Other deletion scenarios cover using [Window's Cipher](https://learn.microsoft.com/en-us/troubleshoot/windows-server/certificates-and-public-key-infrastructure-pki/use-cipher-to-overwrite-deleted-data) `cipher /w:D` to overwrite deleted data.

## Data Recovery
Deleted files will be recovered using [The Sleuth Kit's Autopsy](https://www.autopsy.com/). <br>  

## MFT Output 
The output of the MFT is stored in the file below.
[MFT Output](https://github.com/Passerbyt3/Data-Sanitization/blob/main/20260413124140_MFTECmd_%24MFT_Output%20-%20Copy.csv)
<br>

## Files Used for Deletion
Some files were too large to add to GitHub; they are available on the Google Drive link below.
[Google Drive Link] (https://drive.google.com/file/d/1hcjtkdanCYruHR1iMOlU2t_3XF74DC6x/view?usp=sharing)

## MFTECmd Troubleshooting Guide
Below is a guide I wrote to troubleshoot the 'This app can't run on your PC' error. 
[Guide](https://passerbyt3.github.io/Data-Sanitization/Troubleshoot/)

[Formatting Reference](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


