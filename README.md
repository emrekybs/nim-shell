[![EmreKybs](https://img.shields.io/badge/MadeBy-EmreKybs-yellow)
# Nim-Shell
Reverse shell that can bypass windows defender detection

# Please do not upload to VirusTotal

# 𝗜𝗡𝗦𝗧𝗔𝗟𝗟𝗔𝗧𝗜𝗢𝗡 𝗜𝗡𝗦𝗧𝗥𝗨𝗖𝗧𝗜𝗢𝗡𝗦
    $ apt install nim

# Compilation
nim c -d:mingw --app:gui nimshell.nim


<img src="https://github.com/emrekybs/nim-shell/blob/main/1.png">

Change the IP address and port number you want to listen to in the nimshell.nim file according to your device.

<img src="https://github.com/emrekybs/nim-shell/blob/main/2.png">

# and listen

     $ nc -nvlp 4444
