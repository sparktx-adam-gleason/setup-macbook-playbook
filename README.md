# Ansible playbook for automating a setup of a new MacBook Pro for a rich development experience

This will setup a new laptop for software development.

## Requirements:

1. XCode is installed. Can do so by running `xcode-select --install`
2. Ansible is installed. Can do so by running `pip install ansible`
3. Must be signed into App Store

### How to use:

##### 1. Install XCode and Ansible:

```
 $ xcode-select --install
 $ sudo easy_install pip
 $ sudo pip install ansible
```

##### 2. Run the ansible playbook:

```
 $ git clone https://github.com/fullrobot/setup-macbook-playbook.git
 $ cd setup-macbook-playbook
 $ ansible-playbook setup.yml -i hosts -l local
```

### What this includes:

#### Languages

- Python3
- R
- Java
- GO
- Scala
- Nim

#### Databases

- Postgres
- MySQL
- Redis

#### Virtual Environment managers

- pyenv
- pipenv
- jenv
- plenv

#### Javascript tooling

- Node
- Yarn
- Create React App

#### Code formatters

- Autopep8
- Prettier

#### Productivity apps
- Mac App Store command line
- VSCode
- Slack
- GitHub Desktop
- PostMan
- Google Drive
- Brave browser
- Spotify
- BitWarden
- iTerm2
- Spectacle
- Alfred

