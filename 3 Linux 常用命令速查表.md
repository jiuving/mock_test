# Linux 常用命令速查表

## 1. 文件与目录操作（核心必会）
| 命令 | 作用说明 | 常用示例 |
| :--- | :--- | :--- |
| `ls` | 列出目录内容 | `ls -l` (显示详情) |
| `cd` | 切换目录 | `cd ~/project` (回家目录下的project) |
| `pwd` | 显示当前路径 | `pwd` |
| `mkdir` | 创建新目录 | `mkdir data` |
| `cp` | 复制文件/目录 | `cp file1.txt file2.txt` |
| `mv` | 移动或重命名 | `mv old.txt new.txt` |
| `rm` | 删除文件/目录 | `rm -r folder` (删文件夹需加-r) |
| `touch` | 创建空文件 | `touch test.txt` |

## 2. 文件查看与搜索
| 命令 | 作用说明 | 常用示例 |
| :--- | :--- | :--- |
| `cat` | 查看文件全部内容 | `cat file.txt` |
| `less` | 分页查看（大文件用） | `less bigfile.txt` |
| `grep` | 搜索关键词 | `grep "gene" data.txt` |
| `head` | 查看文件头几行 | `head -n 10 file.txt` |

## 3. 权限与系统
| 命令 | 作用说明 | 常用示例 |
| :--- | :--- | :--- |
| `chmod` | 修改文件权限 | `chmod +x script.sh` (加执行权限) |
| `sudo` | 管理员权限执行 | `sudo apt update` |
| `ssh` | 远程登录服务器 | `ssh user@server_ip` |