# tunn3l_v1s10n

### Approach Used

After downloading the file we can see in our file manager that it does not have any file extension, which means we don't know the file type hence can't open it in any app. We can use `xxd -g 1 tunn3l_v1s10n | head` where 'g' is used to group the bytes and 1 to group them in bits mode, also we can use head tool by piping to get only the first 10 lines and not get the unimportant data. 
![image](https://github.com/UselessAaka/picoCTF-Writeups/assets/148384618/7248d058-4a9f-49de-a79e-4f42486c90f8)
Now we can check [list of file signatures](https://en.wikipedia.org/wiki/List_of_file_signatures) to see what type of file do we have.
![image](https://github.com/UselessAaka/picoCTF-Writeups/assets/148384618/d6cf5a6a-2f9a-447b-bd90-6d1075e1d89d)
