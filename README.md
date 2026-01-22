# Minecraft Coder Pack with Optifine
A ultimate Minecraft Coder Pack with ready latest Optifine and fixed libraries.

# Requirements
- IntelliJ IDEA (Comminuty/Ultimate).
- You should install Java 17 (Amazon Correto). You can install it in Project Structure > Module Java > Download JDK

# How to unlock multiplayer?
First, open projects in IDE. Next you need press CTRL+N, this combination open search file in project. In text field you
should enter "Minecraft" and open it. This is main class. You also can find it in "src/main/java/net/minecraft/".

Second, in this .java file press CTRL+F and enter "isMultiplayerEnabled", and you need find static bool isMultiplayerEnabled.
Open it if it closed, and line of return you need add // and enter "return true;" Also you need unlock chat, in this file find
isChatAllowed or isChatEnabled (by using CTRL+F), and add "return true;".

Re-compile project, and multiplayer button will enabled and connection will allowed.

# Change username in-game
You can change username by add argument --username=YOUR_USERNAME in start configurations.
