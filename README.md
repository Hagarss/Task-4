# Task-4
1. List **all running processes** and save the output to `~/processes.txt`.  
![image](https://github.com/user-attachments/assets/723ca425-6033-4b86-bb82-fd4fd29114e7)

2. Find the **PID (Process ID)** of the `sshd` service.  
![image](https://github.com/user-attachments/assets/2469e818-6372-4015-9f15-eb87dec8ef92)

3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds.  
![image](https://github.com/user-attachments/assets/b222f16d-92a0-4a0a-8e5d-6ef9a80b8a0e)

4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser.
![image](https://github.com/user-attachments/assets/8ce4157f-343f-4aad-8c3e-af22909cf48a)
 
![image](https://github.com/user-attachments/assets/ed6b4763-6832-4790-93d6-f0150829b3eb)
 
5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.  
![image](https://github.com/user-attachments/assets/75337173-e831-47f5-884a-19cbaf2665a6)

6. **Restart the `cron` service** and verify its status.  
![image](https://github.com/user-attachments/assets/46de10de-9380-4125-87e9-2959ff05c1a7)

7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory. 
![image](https://github.com/user-attachments/assets/e52f86b7-b8fe-444c-bfac-d6bc5cc2cef4)
 
8. **Extract** the tarball into `~/logs_backup/`. 
![image](https://github.com/user-attachments/assets/fa6c14de-c15a-4066-b4c0-36491452806b)
 
9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.  
![image](https://github.com/user-attachments/assets/b0ef1f8f-c1a5-42a9-8c1e-f1407e1fd7b6)

10. Compress `~/processes.txt` using `gzip`.  
![image](https://github.com/user-attachments/assets/661bf04a-dca4-4b03-aa78-abb4103e4193)

11. **Decompress** it and compare file sizes using `ls -lh`.  
![image](https://github.com/user-attachments/assets/6bd022ff-7361-46db-a185-b33db3774bce)

12. **Install `htop`** (a process viewer) using your package manager.  
![image](https://github.com/user-attachments/assets/86168b6a-c8f6-4dd2-bfbf-cfdaed632fdd)

13. **Search for the package `nginx`** (or `httpd`) but do not install it. 
![image](https://github.com/user-attachments/assets/65b7f855-5237-4231-a961-da4e68d28533)
 
14. **Remove the `vim` editor** (if installed) and then reinstall it.  
![image](https://github.com/user-attachments/assets/9dcd69d0-7e35-497a-88d9-e1701f4ada58)

15. Use `wget` to download the Linux kernel source:  
    ![image](https://github.com/user-attachments/assets/4584881b-0abd-4798-87fe-b22462474c71)

    ```  
16. Use `curl` to fetch **Google’s homepage** and save it as `google.html`.  
![image](https://github.com/user-attachments/assets/3111907b-e7ea-44ae-ac76-63ed21f33c16)

17. **Create a new VM** (e.g., VirtualBox/Cloud instance), add a user to the `sudoers` group, and run `apt update && apt upgrade`.  
18. **Generate an SSH key pair** using `ssh-keygen`. 
![image](https://github.com/user-attachments/assets/34c8b132-0447-465f-b1d0-71c519ac7055)
 
19. **Copy your public key** to the remote server:  
20. **SSH into the server** and verify with `hostname`.  
21. **Transfer the archived file** (e.g., `archive.tar.gz`) to the remote server using ssh copy way (don’t copy/paste >>> you have to search)


