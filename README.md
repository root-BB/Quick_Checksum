# Quick Checksum
A Small Software to Check File Authenticity
Although I prepared this software to practice on certain Powershell commands, I decided to put it here as it is a very practical use. You can quickly determine whether two files are identical or you can check the file accuracy with a hash code you have.

It is very simple to use; 
- In the first tab in the window that opens, you enter the path to the main file you have and as a result, sie lists the hashes of the main file made with different hash methods.
- If you have a hash code you want to compare, all you have to do is to compare it by pasting the hash code in the right place on the second tab. The result of the comparison automatically determines whether the hash codes are the same or not.
- If you have another file that you can physically compare, just add it to the third tab. As a result, the software automatically compares the hash codes of the two files and tells you if they are the same or not.
- If you want to copy any of the hash codes extracted with them, all you have to do is click on it.

The software uses the Powershell environment, I converted the software in the Source Code to executable due to Powershell's authorization error on some computers. Those who do not receive authorization errors can use Sorce Code directly if they wish.
