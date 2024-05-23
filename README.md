# Securing File Permissions in the Projects Directory

## Objective
• Modify Linux file permissions to control read, write, and execute access for users, groups, and others

### Skills Learned

• Analyzing File and Directory Details
• Understanding Permission Strings
• Modifying Directory Permissions
• Managing Hidden File Permissions
• Verification of Changes

## Steps

1) Check File and Directory Details

 Use ls -la to list all files and directories, including hidden ones.
 Identify specific files and directories needing permission updates (e.g., "Drafts" directory and ".project_x.txt" hidden file).
 
 2) Describe and Understand Permission Strings
 
 Analyze the permission strings to determine current access levels for the owner, group, and others.
 Deconstruct permission strings to understand their structure and meaning.
 
3) Change Directory Permissions

 Modify the "Drafts" directory permissions to restrict access:
 Use chmod g-x drafts to remove execute permission for the group.
 Verify changes using ls -la.

4) Change Hidden File Permissions

 Update permissions for the hidden file ".project_x.txt":
 Use chmod u-w,g-w,g+r .project_x.txt to adjust read and write access.
 Verify changes using ls -la.

5) Verify and Document Changes

 Ensure all permission updates are correctly applied.
Double-check the updated permissions with ls -la.
Document the process and results to ensure clarity and traceability.

[File permissions in Linux.pdf](https://github.com/chriske00/Linux-file-permission-modification/files/15414040/File.permissions.in.Linux.pdf)







