在Mac上启动和停止Jenkins
启动
```
sudo launchctl load /Library/LaunchDaemons/org.jenkins-ci.plist
```
停止
```
sudo launchctl unload /Library/LaunchDaemons/org.jenkins-ci.plist
```
