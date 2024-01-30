I am updating the process of setting up the ELK stack here:


- Updating the Java path in the zsh:
java -version
--
 openjdk version "11.0.21" 2023-10-17
 OpenJDK Runtime Environment Homebrew (build 11.0.21+0)
 OpenJDK 64-Bit Server VM Homebrew (build 11.0.21+0, mixed mode)

- Path to java using command: /usr/libexec/java_home
 /opt/homebrew/Cellar/openjdk@11/11.0.21/libexec/openjdk.jdk/Contents/Home

- open zsh profile file:
 vi /Users/harshabhargavyarramsetty/.zshrc 

# in this file update the following line:
 export JAVA_HOME =  /opt/homebrew/Cellar/openjdk@11/11.0.21/libexec/openjdk.jdk/Contents/Home

- Use the following code:
 source ~/.zshrc  
 echo $JAVA_HOME
-----------------------
