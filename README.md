# Git and Git-Hub Setup Guide
## In the Git Bash terminal
### Generate key

- ```ssh-keygen -t rsa -b 4096 -C "emailaddress"```

### Link key

- Navigate into folder containing key with ```cd ~/.ssh```
- Use ```cat id_rsa.pub``` to get public key to copy
- On Github, go to Settings and then SSH and GPG keys
- Click on "New SSH key"
- Paste the copied key and title it
