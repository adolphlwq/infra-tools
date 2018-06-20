# Infrastructure tools
use ansible to manage and init infrastructures

## Requirements
- make
- ansible

## Steps
1. clone repo
```
git clone https://github.com/adolphlwq/infra-tools.git
```
2. change default valus in dir `global_vars/all`
```
---
demo_user: your_user
demo_pass: your_pass
dotfiles_dest: /home/your_user/workspace/githubwp/dotfiles
```
3. change host in `hosts`
```
[ubuntu]
example.org
```
5. run `make start` to init your Linux server