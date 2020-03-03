SPRINGBOOG BOOK
=====
#Machine Setup


##สำหรับคนใช้ OS X
```
 > brew cask install java
 > brew cask install intellij-idea-ce
 > brew install maven
 > brew install protobuf
```


##สำหรับคนใช้ Windows (Power Shell)
```
 > Set-ExecutionPolicy RemoteSigned -scope CurrentUser
 > Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh/')
 > scoop bucket add java
 > scoop install openjdk
 > scoop install maven
 > scoop bucket add extras
 > scoop install protobuf
```


##ProtobufCompile
```
protoc --java_out=src/main/java protobuf/*.proto
```

@ COPYRIGHT 2020, PEERAPAT ASOKTUMMARUNGSRI
