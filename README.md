# Linux-Admin-101

These instructions are customized for the NICE Challenge Exercise

Linux Administration 101 to add users, add to group, and update (C___OS)

*Troubleshooting*
- If the terminal doesn't open restart the Prod-Web

## Finding Out What Linux You Have
1. the command cat shows what is written in a file
2. /etc has all the system's config in it
  -command: $ cat /etc/issue

## Adding User
1. useradd vs adduser
  - useradd is native binary and adduser is a perl script that utilizes useradd
2. command: $ adduser __________ (if this doesn't work: put sudo in front)
  - ex: $ sudo adduser HenryG

## Giving The User A Password
1. Use the command "passwd"
  - This command could be used to assign or change password for an account
2.command: $ passwd (username)
  - ex: passwd HenryG
  
## Assigning User to Group
1. Use the command "groups"
  - Shows what groups you are in
  - $ groups
2. adding a user to a existing group: "usermod"
3. command: usermod -aG (group name) (user name)
4. Alt. command: usermod -a -G (group name) (user name)
  ex: usermod -aG sudo HenryG
  
## Updating your system
1. Depending on what Linux system you are using the update command is different.

