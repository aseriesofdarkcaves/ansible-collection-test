# ansible-collection-test

This repo shows how to initialise a custom Collection.

## Ansible installation
Install Ansible through Python pip - not global, just for your user:
```shell
python3 -m pip install --user ansible
```

## The Collection
Messing about by creating a custom collection of stuff that does mostly nothing useful.

I used this to create the collection skeleton:
```shell
# init the directory
ansible-galaxy collection init aseriesofdarkcaves.ansible_collection_test
```

## More information on Collections
Read [this](https://docs.ansible.com/ansible/2.9/dev_guide/developing_collections.html).
