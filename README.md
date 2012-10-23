Openstack-horizon-zh_CN-language
================================

这是openstack的web项目-Horizon的汉化文件，基于ESSEX版本，Ubuntu12.04下安装后的版本。
使用方法：
1、请放到：/usr/share/pyshared/horizon/locale/zh_CN/LC_MESSAGES/django.po
2、复制到简体中文目录后，编译po文件：msgfmt --statistics --verbose -o django.mo django.po

具体请参考该文档：http://www.cnblogs.com/cszzy/archive/2012/05/22/2513466.html