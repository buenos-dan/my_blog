# tmux learning
tmux是一个终端复用软件，它的一个直观的用处是通过一个终端登陆远程主机并运行tmux后，在其中可以开启多个控制台而无需在浪费多余终端来连接远程主机。
## how to install?
```
sudo apt-get install tmux
```
## how to use?
5. list shortcuts
```
ctrl+b ?
```
press q to quit
1. create a new tmux
```
tmux new -s name
```
2. quit a tmux
```
ctrl+b &
```
3. log in tmux
```
tmux a -t name
tumx attach
```
4. split window 
```
ctrl+b "
ctrl+b %
```




