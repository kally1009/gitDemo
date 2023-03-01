## Installing git
---
#### https://github.com/git-guides/install-git



- Windows Install

- Mac Install

- Linux Install (including WSL)

    *The one I will show and use. Refer to docs for other install instructions.*

```
sudo apt-get update
sudo apt-get install git-all
git version
```
---
## Setting up SSH (For those who need/want to):

```
ssh-keygen
```

### Default saved in .ssh folder under /home/user/.


Files generated:
* id_rsa  and “id_rsa.pub

user is replaced with your username. 
```
cd /home/user/.ssh/
ls
cat id_rsa.pub
```
Copy contents of id_rsa.pub and put into authenticator. In github it is under settings -> SSH and GPG Keys -> New SSH Key. 
