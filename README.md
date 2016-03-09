# TipsNTricks

1. Without putty access remote server: \n
    -from windows cmd \n
        - ssh <username>@<ip> \n

2. Copy files from remote server to local with ssh
    -from windows cmd
        - scp <username>@<ip>:/path/to/file/in/server  /local/path/to/save/file
3. Install oracle jdk in ubuntu \n
    sudo add-apt-repository ppa:webupd8team/java -y  ##Add repository \n
    sudo apt-get update ## update the repo \n
    sudo apt-get install oracle-java8-installer ##install java from oracle \n
    
    To automatically set up the Java 8 environment variables \n
        sudo apt-get install oracle-java8-set-default
