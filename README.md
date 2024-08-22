# Encrypting-a-file-system

## Objective

 Will be encrypting a file system or folder using EFS that is built into Windows. 


### Skills Learned

- File encryption 

### Tools Used

- Microsoft 10 VM
- Bitlocker


## Steps
1. We want to be sure that NFTS is running on the system.
2. Navigate to the Windows Desktop and press the <kbd>Windows</kbd> key and the <kbd>E</kbd> key to open File Explorer.
3. Go to **This PC** and we will be using the C Drive, **Local Disk (C:)**. Right click and select **Properties**
4. View the file system and confirm NTFS.
5. Create a folder on the Desktop labeled **Private Stuff** and add some documents into the folder.
6. Right click on the **Private Stuff** folder and select **Properties**->**Advanced**. Click on the **Encrypt contents to secure data option**. Select **Apply**, then **Ok**.
7. Notice that the **Private Stuff folder** has a little lock symbol on it, indicating that it is now encrypted.

Tip: Instead of encrypting the entire drive (can be resource intenstive) encrypt the file or folder. 

**Bitlocker option on Windows**
![image](https://github.com/user-attachments/assets/1ef32043-7042-42c1-aff6-9be301c5d9f9)
