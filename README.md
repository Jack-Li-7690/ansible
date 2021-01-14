# ansible
### 簡易的ansible 教學
>#### 階層概念
```
workspace  
├── ansible.cfg  
├── inventory  
├── playbook.yml  
└── roles  
    |── os-initial 
    │   └── tasks
    │       └── main.yml
    └── vote-dapp
        └── tasks
            └── main.yml
```
執行語法： ansible-playbook  -i nginx.yml



更多的rule 可參考：

[ansilbe-galaxy](https://blog.csdn.net/weixin_43557605/article/details/103767610)`