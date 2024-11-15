## Exercise 1: Importing a Hash Database of Known Files in Autopsy
### Description
In this exercise, I imported a hash database of common files into Autopsy. This database, from the National Software Reference Library , contains hashes of typical files. It helps investigators ignore standard files and focus on anything unusual or suspicious on a suspect’s device.

### Why This is Useful
Hash databases let investigators filter out common files automatically, so they can focus on unique or suspicious ones. This saves time and avoids wasting effort on harmless files.

### Screenshot
![Hash Set Screenshot](https://github.com/IanW25/df-mod4-tools/blob/main/Images/Mod%204%20Excercise%201%20Screenshot.png)


## Exercise 2: Creating a Hash Database of Evidence Files in Autopsy
### Description
In this exercise, I used Autopsy to create a hash database for suspicious files found in the evidence file. I tagged the "Special Project-A" images, generated their hashes, and saved them in a new database. This database helps quickly find the same files on other devices, making it easier to track evidence.

### Why This is Useful
Creating a hash database of evidence files helps investigators quickly spot the same files on other devices or cases. This makes it easier to connect investigations and work more efficiently.

### Screenshot
![Screenshot of Autopsy Hash Database with Evidence Files](https://github.com/IanW25/df-mod4-tools/blob/main/Images/Mod%204%20Excercise%202%20Screenshot.png)

## Exercise 3: Matching File Remnants with a Hex Editor
### Description
In this exercise, I used ImHex to calculate hash values for files. I created a Word document and generated its SHA-256 hash to check its integrity. Then, I calculated the hash for the first sector of the Jefferson Quotes.doc file. This shows how investigators can use hashes to match file fragments, even if the original file is deleted.

### Why This is Useful
When a file is deleted, only the link to it is removed, but the data often stays on the storage until it gets overwritten. Investigators can use hashes to match file fragments to the original file, helping connect the evidence to a suspect or device.

### Screenshots
1. Full File Hash:
   ![File Hash Screenshot 1](https://github.com/IanW25/df-mod4-tools/blob/main/Images/Mod%204%20Excercise%203%20Test%20Doc%20Hash%20Screenshot.png)

   ![File Hash Screenshot 2](https://github.com/IanW25/df-mod4-tools/blob/main/Images/Mod%204%20Excercise%203%20Test%20doc%20hash%20ImHex%20Screenshot.png)

2. First Sector Hash:
   ![First Sector Hash Screenshot](https://github.com/IanW25/df-mod4-tools/blob/83d13209dd4cc33661da5c728493b803c15cea5e/Mod%204%20Excercise%203%20Jeff%20Hash%20Screenshot.png)

## Exercise 4: Simple Encryption Using CyberChef

### Description
In this exercise, I used CyberChef to encrypt and decrypt a message with Vigenère encryption. Encryption is a way to hide data, and investigators need to know how to spot and decode it to find important evidence.

### Importance of Bit Manipulation in Digital Forensics
Even simple encryption can hide important evidence. Knowing how to spot and decode it is key to finding hidden data and uncovering tampering. Tools like CyberChef help make analyzing encrypted content faster and easier.

### Screenshot
Here’s a screenshot of the encryption process in CyberChef:
![CyberChef Encryption Screenshot](https://github.com/IanW25/df-mod4-tools/blob/main/Images/Mod%204%20Excercise%204%20Screenshot.png)
