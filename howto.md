# Install AWS cli

### Download the file using the curl command. The -o option specifies the file name that the downloaded package is written to. In this example, the file is written to AWSCLIV2.pkg in the current folder.

```bash
$ curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
```

### Run the standard macOS installer program, specifying the downloaded .pkg file as the source. Use the -pkg parameter to specify the name of the package to install, and the -target / parameter for which drive to install the package to. The files are installed to /usr/local/aws-cli, and a symlink is automatically created in /usr/local/bin. You must include sudo on the command to grant write permissions to those folders.
```bash
$ sudo installer -pkg ./AWSCLIV2.pkg -target /
```

### To verify that the shell can find and run the aws command in your $PATH, use the following commands.
```bash
$ which aws
$ aws --version
```

#### to config aws: 
```bash
$ AWS access key id : [id]
$ AWS secret access key : [access-key]
$ default ragion name : [name]
$ default output format : [json]
```

