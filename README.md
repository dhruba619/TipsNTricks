# TipsNTricks

1. Without putty access remote server:
    -from windows cmd 
        - ssh <username>@<ip>

2. Copy files from remote server to local with ssh
    -from windows cmd
        - scp <username>@<ip>:/path/to/file/in/server  /local/path/to/save/file
3. Install oracle jdk in ubuntu
    sudo add-apt-repository ppa:webupd8team/java -y  ##Add repository
    sudo apt-get update ## update the repo
    sudo apt-get install oracle-java8-installer ##install java from oracle
    
    To automatically set up the Java 8 environment variables
        sudo apt-get install oracle-java8-set-default
