# alx_be_shell
## Shell_permissions
### 0. My name is Betty

Create a script that switches the current user to the user betty.
- You should use exactly 8 characters for your command (+1 character for the new line)
- You can assume that the user betty will exist when we will run your script

``` 
su betty
```

- Directory: shell_permissions
- File: 0-iam_betty

### 1. Who am I 

Write a script that prints the effective username of the current user.

```
whoami
```

- Directory: shell_permissions
- File: 1-who_am_i

### 2. Empty!

- Write a script that creates an empty file called hello.

```
touch hello
```

- Directory: shell_permissions
- File: 4-empty

### 3. Execute

Write a script that adds execute permission to the owner of the file hello.

- The file hello will be in the working directory

```
chmod u+x hello
```

- Directory: shell_permissions
- File: 5-execute

### 4. Multiple permissions

Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

- The file hello will be in the working directory

```
chmod u+x,g+x,o+r hello
```

- Directory: shell_permissions
- File: 6-multiple_permissions

### 5. John Doe

Write a script that sets the mode of the file hello to this:

- rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

- The file hello will be in the working directory
- You are not allowed to use commas for this script

```
chmod 753 hello
```

- Directory: shell_permissions
- File: 9-John_Doe


