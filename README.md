# lxy
learn
@echo off

netsh winsock reset

ipconfig /flushdns

netsh interface ip set dns 本地连接 static 114.114.114.114

netsh interface ip add dns 本地连接 233.5.5.5
