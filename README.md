# Java Packet Capturer (PCAP4J)

# A simple packet capturing tool written in Java using the PCAP4J library.
# Designed for quick packet inspection and experimentation on Linux and macOS.

# --------------------------------------------------
# Requirements
# --------------------------------------------------
# - Java (JDK 8+)
# - sudo/root privileges (required for packet capture)
# - Tested on:
#   - Raspberry Pi 3B+
#   - Raspberry Pi 4
#   - macOS (MacBook Pro)

# --------------------------------------------------
# Linux (Raspberry Pi) Setup & Run
# --------------------------------------------------

sudo apt-get update
sudo apt-get install -y git default-jdk

git clone https://github.com/exie1122/javanetworking.git
cd javanetworking

# Fix jar filename (if needed)
mv "javanetworking .jar" javanetworking.jar

# Run
sudo java -jar javanetworking.jar

# --------------------------------------------------
# macOS Setup & Run
# --------------------------------------------------

cd ~/Downloads/javanetworking-main

# Optional: rename jar to remove spaces
mv "javanetworking .jar" javanetworking.jar

# Run
sudo java -jar javanetworking.jar

# --------------------------------------------------
# Notes
# --------------------------------------------------
# - Requires sudo because packet capture needs raw socket access
# - Works on both Linux (Raspberry Pi) and macOS
# - Uses PCAP4J under the hood

# --------------------------------------------------
# Screenshots
# --------------------------------------------------
# macOS:
# https://github.com/exie1122/javanetworking/assets/165369920/73324630-7d9c-4211-9824-4196019f23c7

# Raspberry Pi:
# https://github.com/exie1122/javanetworking/assets/165369920/2d872538-5411-4020-9e41-e4477bbfeea1
