# ansible-playbook-rails-mac

## Description
Mac OS X に rbenv, ruby-build, ruby, rails をインストールするansible playbookです。

## Requirement

### xcode-select

```
$ xcode-select --install
```

### homebrew

```
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
