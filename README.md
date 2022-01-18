# Create-File-With-Parent-Name

## Purpose
This is designed to create child files within all of the parent directories underneath the highest level folder. The child files will inherit the parent folder's name. The script creates txt documents but you can adjust that to be whatever file type you need.

## Why?
I found this to be helpful when indexing and searching across a massive amount folders with tens of thousands of attachments. I had to transfer a few million attachments between file management suites and this helped when interacting with the API of the new suite. It also speeds up the Windows search process tremendously while taking up virtually no space.

## How to Use
Simply change the top directory after the Get-ChildItem function to be the full pth of whatever directory you're working in. This will recurse everything underneath it.
This can be enhanced to add details or properties to the files as well as text into them upon creation. I had done that in the past when I knew the files would be transferring onto Linux so that I could grep them for specific text.
