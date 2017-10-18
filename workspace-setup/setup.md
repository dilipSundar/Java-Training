This read has the workspace set up instructions.

## Java Installation in Mac

### How to check the java version in the machine ?

```
java -version
```

The above command will display the below results.  

```
java version "1.8.0_131"
Java(TM) SE Runtime Environment (build 1.8.0_131-b11)
Java HotSpot(TM) 64-Bit Server VM (build 25.131-b11, mixed mode)
```

### How to check the machine is 32 bit or 64 bit ?

- Run the below command to check the MAC os is a 32 bit or 64 bit ?

```
getconf LONG_BIT
```

https://apple.stackexchange.com/questions/12666/how-to-check-whether-my-intel-based-mac-is-32-bit-or-64-bit


### How to download/install Java JDK for mac ?

- Go to the below link and download the appropriate Java JDK.

http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

- Install the image file.
- Check the Java version again. This should display the installed version of the Java.

### How to setup the java path manually ?

- Add the below line in the **.bash_profile** file.

```
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_131.jdk/Contents/Home
```

## Intellij Installation in Mac

### Download the intellij in Mac:

- Go to the below link and download intellij.

https://www.jetbrains.com/idea/download/#section=mac

- Select the **OS** as **MAC**

- Click on the Community version **Download** button.

### Installation of Intellij:

- Double click on the image icon
- Installation will be complete.
