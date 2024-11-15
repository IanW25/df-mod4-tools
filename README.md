## Exercise 1: Importing a Hash Database of Known Files in Autopsy
### Description
In this exercise, I imported a hash database of common files into Autopsy. This database, from the National Software Reference Library , contains hashes of typical files. It helps investigators ignore standard files and focus on anything unusual or suspicious on a suspect’s device.
### Why This is Useful
Hash databases let investigators filter out common files automatically, so they can focus on unique or suspicious ones. This saves time and avoids wasting effort on harmless files.
### Screenshot
![Hash Set Screenshot](Images/Mod%204%20Excercise%201%20Screenshot.png")

## Exercise 2: Creating a Hash Database of Evidence Files in Autopsy
### Description
In this exercise, I used Autopsy to create a hash database for suspicious files found in the evidence file. I tagged the "Special Project-A" images, generated their hashes, and saved them in a new database. This database helps quickly find the same files on other devices, making it easier to track evidence.
### Why This is Useful
Creating a hash database of evidence files helps investigators quickly spot the same files on other devices or cases. This makes it easier to connect investigations and work more efficiently.

### Screenshot
![Screenshot of Autopsy Hash Database with Evidence Files](Images/Mod%204%20Excercise%202%20Screenshot.png")

## Exercise 3: Matching File Remnants with a Hex Editor
### Description
In this exercise, I used ImHex to calculate hash values for files. I created a Word document and generated its SHA-256 hash to check its integrity. Then, I calculated the hash for the first sector of the Jefferson Quotes.doc file. This shows how investigators can use hashes to match file fragments, even if the original file is deleted.

### Why This is Useful
When a file is deleted, only the link to it is removed, but the data often stays on the storage until it gets overwritten. Investigators can use hashes to match file fragments to the original file, helping connect the evidence to a suspect or device.

### Screenshots
1. Full File Hash:
   ![File Hash Screenshot 1](C:\Users\IW1785336\OneDrive - Oracle Corporation\Desktop\df-mod4-tools\df-mod4-tools\Images\Mod 4 Excercise 3 Test doc hash ImHex Screenshot.png)

   ![File Hash Screenshot 2](C:\Users\IW1785336\OneDrive - Oracle Corporation\Desktop\df-mod4-tools\df-mod4-tools\Images\Mod 4 Excercise 3 Test Doc Hash Screenshot.png)

2. First Sector Hash:
   ![First Sector Hash Screenshot](C:\Users\IW1785336\OneDrive - Oracle Corporation\Desktop\df-mod4-tools\df-mod4-tools\Images\Mod 4 Excercise 3 Jeff Hash Screenshot.png)
