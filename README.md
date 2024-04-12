# HMCL on Ubuntu



### Download and Launch

1. `sudo apt install openjdk-11-jdk` to install `openjdk-11`

   - You may need to modify the version in accordance with the version of HMCL pkg 

      

2. Move the .jar file of HMCL to the targeted directory (here the path is: ~/Downloads/mc) 

   - Find the latest version of HMCL launcher [here](http://www.mcbbs.net/thread-142335-1-1.html)

     

3. The launch will be started by `java -jar HMCL-3.5.5.jar`

   - Replace HMCL-3.5.3 with the right version number when you are downloading launcher on-line

   

4. (optional) Use `tar xvzf microsoft-jdk-17.0.3-linux-x64.tar.gz `  to uncompress java-17 pack 

   - ##### See [here](https://blog.csdn.net/weixin_50843918/article/details/122262306) if you wish to add Java-17 to your system path

     

5. Start launcher and 

   - Download the desired version of game (or you may use a soft link pointing to your `.minecraft` directory elsewhere) 
   - Change Java directory to the the correct JAVA directory (e.g. `/Downloads/mc/jdk-17.0.3+7/bin/java`)

   

   

### To create a desktop shortcut

The shortcut involves 

​	1: the icon image, 

​	2: minecraft.sh,

​	3: mincraft.desktop.



#### You need to 

1. Replace the ***directory and version number*** in minecraft.sh with your own one

2. Replace the ***directory*** in minecraft.desktop

   - You may also replace the shortcut icon with other pic

3. `sudo chmod +x minecraft.sh` to provide access

4. ```bash
   sudo chmod +x minecraft.desktop
   sudo cp minecraft.desktop /usr/share/applications
   ```

