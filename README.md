## Git-Example
This repo is to store some lab with Git

### Lab 01: Install Git

- Install Git on Ubuntu

```
sudo apt update
sudo apt install git -y
git --version
```

- Install Git on CentOS

```
sudo yum check-update
sudo yum install git -y
git --version
```

### Lab 02: Configuration

- Configure username, email

```
git config --global user.name <User Name>
git config --global user.email <Email>
```

- Configure using Vim as editor

```
git config --global core.editor “vim”
git config --global push.default simple
```

### Lab 03: First commit

- Workflow:
  - Fork a remote repo to Github private
  - Clone the repo
  - Edit files
  - Commit and push to Github
