Script Descriptions
0. 'su betty' allows us to change the current user to betty
1. 'whoami' is a command which allow the user to see his own username
2. 'groups' is a command which allow the user to see all the groups he's currently part of
3. 'chown betty hello' chown allow the user to put betty as the owner of the hello file
4. 'touch hello' allow the user to create a file called hello
5. 'chmod u+x hello' chmod allow the super user to add the execute permission to the current user for the hello file
6. 'chmod ug+x,o+r hello' chmod allow the super user to give the current user and the group he's in to execute the hello file, he also gave the other users the permission to read the hello file.
7. 'chmod ugo+x hello' The super user gave the current user, the group he's in and the other users to execute the hello file.
8. 'chmod 007 hello' The super user made use of the octal system to give all permissions on the hello file to the other users
9. 'chmod 753 hello' like previously, the super user used the octal system to give permissions however this time he gave all permissions to the owner of the file, the reading and execution permissions to the groups and he gave writing aswell as execution permissions for the other users.
10. 'chmod --reference=olleh hello' this command is used to take olleh's file permissions and to copy them onto the hello file.
11. 'chmod -R ugo+x */*' is a command which will add the execute permission to all users on the subdirectories of the current directory.
12. 'mkdir -m751 my_dir' Ceci permet de cr√©er un √©√pertoire mm√ my_dir avec les permissions deja parametr√es pour ce repertoire.
