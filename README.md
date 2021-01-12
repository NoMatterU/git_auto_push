# git_auto_push

### 该脚本会遍历当前目录下所有文件夹，再根据ini文件里配置的信息pull和push指定分支
### 会根据时间生成commit备注，对未提交的代码add，commit，未解决冲突提交报错
### 排除不想操作的文件夹

# branch.ini
### 支持#注释 以行为单位进行读取信息
### pull_branch: + 需要pull的分支名
### push_branch: + 需要push的分支名
### exclude_dir: + 需要排除的文件夹名
