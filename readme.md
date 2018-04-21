## Common Commands


```shell
ls <path>			# Command
ls ./			# Show Current Directory
ls -a ./			# Show Invis Files of Current Directory
```

```shell
cd <path>			# Command
cd ./Desktop		# Relative Path Changing Directory 
```

### Paths

##### Current User's Home Folder

```/Users/cchapman/``` is the same as ```~```

##### Absolute Paths

The entire path from the root ```/``` of your hard drive to the folder you are targeting.

Example: ```/Users/cchapman/Desktop/Zero_to_Git```

##### Relative Paths

```./``` or ```.``` prefix for Relative Path. Means "My current working directory"

```shell
cd ./Desktop
```

##### Parent Directory

```..```

```shell
cd ..			# Goes to the Parent Folder (directory)
```

## BE CAREFUL

```shell
rm /
```

## Git Commands

One time commands

```shell
git config --global core.editor "nano"
git config --global user.name "Chapman"
git config --global user.email Chapman@apextion.com

```

Use once when starting a git repo

```shell
git init
```

Use often, Common Commands.

```shell
git init
git status
git add <path>
git commit -m "Some message here (Start with a verb)"
```