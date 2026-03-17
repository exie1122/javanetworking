PCAP4J Packet Tool
A simple packet capturer built in Java using PCAP4J.

Root Privileges Required: This tool requires sudo to access network interfaces for packet capture.
Tested Platforms (2024-05-27)
Raspberry Pi: 3B+, 4

macOS: MacBook Pro

# 🚀 Getting Started
🍎 macOS
```
cd ~/Downloads/javanetworking-main
sudo java -jar "javanetworking.jar"
```
🍓 Raspberry Pi / Linux
```
# Update and install dependencies
sudo apt-get update && sudo apt-get install git default-jdk -y
```

# Clone and enter directory
```
git clone https://github.com/exie1122/javanetworking.git
cd javanetworking/
```

# Rename JAR to fix spacing and run
```
mv 'javanetworking .jar' javanetworking.jar
sudo java -jar javanetworking.jar
```
📋 Prerequisites
Java: JDK 8 or higher.

Network Library: libpcap (Standard on macOS and Raspberry Pi OS).
