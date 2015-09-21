# recursive_7zip_batch
A simple Windows batch script I use to extract archives in subfolders.

# Usage
This Windows batch script requires 7zip to be installed. Drop this file in the folder which has subfolders containing archives you wish to decompress.

# Customization
Change the path: "C:\Program Files\7-zip\7z.exe" to whatever reflect your setup.

If you wish to include archives other .rar or .zip, you should be able to simply add them to the list of file types, however, your mileage may vary based on how 7zip handles them. For example, adding *.tar might just extract the tar, leaving the compressed files inside of it untouched.

Also, by default this batch file will pause and ask the user before overwriting any files. This could probably be overridden by adding the "-y" flag to the end of the call of 7zip.

