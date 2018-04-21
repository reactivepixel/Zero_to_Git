

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

To access the parent Dir use the ```..``` to reference it.

Example: 

```shell
cd ..			# Goes to the Parent Folder (directory)
```

## BE CAREFUL

```shell
rm /
```