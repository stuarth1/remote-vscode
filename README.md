# remote-vscode


1. Download Remote VS Code from Visual Studio
2. Setup an AWS Server
3. Run the following commands 
      sudo wget -O /usr/local/bin/rmate https://raw.github.com/aurora/rmate/master/rmate
      sudo chmod a+x /usr/local/bin/rmate
4. On your local machine go into the ~/.ssh folder and either make a config file or create a config file. In the config paste this

`Host *
    RemoteForward 52698 localhost:52698`

5. In your visual studio open up the command pallete and run Remote: Start Server
     The command I used is `f1` to get there then typed Remote: Start Server 
