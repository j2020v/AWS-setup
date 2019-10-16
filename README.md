# AMAZON WEB SERVICE (AWS) BASIC

## Step 1:
- Log in AWS
- Obtain SSH key pair
- Set up an instance
- Then, SSH into AWS

```
ssh -i ~/.ssh/<key_file> ubuntu@xxx-xx-xxx-xx-xxx.eu-west-2.compute.amazonaws.com
```

## Step 2:
- Moving files between local computer and instance (AWS)

```
scp -i path/to/key_file/to/copy <file> ubuntu@xxx-xx-xxx-xx-xxx.eu-west-2.compute.amazonaws.com
```

- Moving folders between local computer and instance (AWS)

```
scp -i path/to/key_file/to/copy -r <folder> ubuntu@xxx-xx-xxx-xx-xxx.eu-west-2.compute.amazonaws.com
```

## Step 3:

- You can now run the <file> / <folder> that you have moved from your local pc in SSH
