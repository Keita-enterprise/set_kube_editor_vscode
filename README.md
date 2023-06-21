# Open gitbash and run the following commands 
# 1
  setx KUBE_EDITOR "code"
# 2 
 echo "export KUBE_EDITOR=code" >> ~/.bashrc
 source ~/.bashrc
# 3
 echo $KUBE_EDITOR
# 4 From now on, when you run kubectl edit <resource>, it will open the resource's configuration in Visual Studio Code instead of Notepad
