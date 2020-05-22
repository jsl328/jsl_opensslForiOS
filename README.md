# jsl_opensslForiOS

1.将include文件拖入工程根目录中
2.将libcrypto.a 和 libssl.a拖入工程的Frameworks中
3. 在Library Search Paths中添加$(inherited)  和$(SRCROOT)
4.在Header Search Paths中添加include
5.Always Search User Path设置为Yes
