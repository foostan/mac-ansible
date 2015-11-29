# mac-ansible

## before provisioning
install xcode

```shell
sudo xcodebuild -license
```

install homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

install ansible
```
brew update
brew install ansible
```

download ansible playbooks
```
brew install git
git clone https://github.com/foostan/mac-ansible.git
```

## provisioning
```
cd mac-ansible
ansible-playbook -i hosts localhost.yml
```
