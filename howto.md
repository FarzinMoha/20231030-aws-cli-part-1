# Install AWS cli

##### Install AWS cli
```bash
$ curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
$ sudo installer -pkg ./AWSCLIV2.pkg -target /
```

##### To check install
```bash
$ which aws
$ aws --version
```

##### to config aws: 
```bash
$ AWS access key id : [id]
$ AWS secret access key : [access-key]
$ default ragion name : [name]
$ default output format : [json]
```

##### describe resources: 
```bash
$ aws ec2 describe-instances
$ aws memorydb describe-clusters --output table
```



