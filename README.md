# elementary-ansible

first, install add repo and latest version of ansible for ubuntu 16.04

```
sudo apt-get update &&
sudo apt-get install -y software-properties-common git git-core &&
sudo apt-add-repository -y ppa:ansible/ansible &&
sudo apt-get update &&
sudo apt-get install --install-recommends -y ansible
```

```
ansible-pull -o -vvv -U https://github.com/myersg86/elementary-ansible.git local.yml
```