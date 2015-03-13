# ansible-playbook-rails-mac

## Description
Mac OS X に rbenv, ruby-build, ruby, rails をインストールするansible playbookです。

## Requirement
### homebrew

```
$ xcode-select --install
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

途中でパスワードの入力が必要です。

### Ansible

```
$ brew install ansible
```

## Usage

```
$ git clone git@github.com:KaitoWatanabe/ansible-playbook-rails-mac.git
$ cd ansible-playbook-rails-mac
$ ansible-playbook playbook.yml -i hosts
```
