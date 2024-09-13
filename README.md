_Linux Essentials Documentation_

_Introduction_

This documentation provides a step-by-step guide to performing various Linux tasks, including file and directory management, user and group administration, and system information.

_Prerequisites_

- Basic understanding of Linux operating system
- Access to a Linux terminal or command line interface

_File and Directory Management_

- `mkdir`: Create a new directory (e.g., `Project_Linux`)
- `cd`: Change directory into the created directory
- `ll`: List files in the directory with permissions
- `cat`: Display contents of a file

- ![mkdir, cat, cd](https://github.com/user-attachments/assets/b829779c-83c0-4d15-b718-d5289440cc98)
- `cd..`: To return to the previous directory which is `Project_Linux`
- `touch`: Create new files (e.g., `S3` and `EC2`)
- `rm`: Remove the file `S3` and `EC2`
- `rm -r`: Recursively delete a directory `People.txt`

- ![touch,rm](https://github.com/user-attachments/assets/d5df6a46-523d-4291-acb3-d3737ef522db)

- `sudo`: It allows user to run commands with privilege that only root user have.
- `chmod`: Change file permissions `People.txt`
- `chown`: Change ownership of a file `People.txt`

- ![chmod  chown](https://github.com/user-attachments/assets/cd798cdc-8d88-40ec-92b2-55d7264bc705)

  

_User and Group Administration_

- `useradd`: Add a new user with a shell `Seun`
- `groupadd`: Add a new group `developers`
- `tail -n 1`: Display the last system log entry
- `/etc/passwd`: View user information
- `passwd`: Set a password for a user
- `/etc/group`: View group information
- `usermod -aG`: Add a user`Seun` to a group `developers`
- `userdel`: Delete a user
- `groupdel`: Delete a group

- ![useradd, group](https://github.com/user-attachments/assets/097fd9f8-1cb0-4809-a876-224864e3ec50)

Network utilities 

- `ifconfig`: Check the IP address of the host
- `nslookup`: Query DNS records for a domain name

- ![ifconfig, nslookup](https://github.com/user-attachments/assets/e396d664-5db1-4ac7-9630-e15e7ef5ae33)

- `ping`: Ping an IP address to test host reachability

- ![ping](https://github.com/user-attachments/assets/51f5aa1a-fb62-48e5-a4e8-8fc282e6f2e3)

- `ssh`: Securely connect to a host

- ![ssh](https://github.com/user-attachments/assets/fe3654f9-3324-47ea-893b-af72a2eed1b5)


_Conclusion_

By following this documentation, you have learned essential Linux commands and concepts for managing files and directories, administering users and groups, and network utilities.
