# ec2-ansible

とりあえずEC2に流すやつ。最低限。

## Run

1. hostsにIPを追加する。

2. Dry-Run
```
ansible-playbook --private-key=~/.ssh/private/key.pem -i ./hosts site.yml --check
```

3. Run
```
ansible-playbook --private-key=~/.ssh/private/site.pem -i ./hosts site.yml
```



