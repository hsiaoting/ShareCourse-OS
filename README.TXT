ShareCourse: OS 
作業一：
1) 程式碼說明
code from:
http://asm.sourceforge.net/intro/hello.html

要編譯成64bit binary program 的指令修改為：
$ nasm -f elf64 -o assign1.o assign1.asm 
$ ld -o assign1 assign1.o

Ref.:
http://asm.sourceforge.net/intro/hello.html
http://blog.markloiseau.com/2012/05/64-bit-hello-world-in-linux-assembly-nasm/

2) Linux Distribution 的選擇：
個人使用偏愛 Debian based (ex: Ubuntu) distro, 但是因為公司開發規範，故工作上使用 CentOS 居多。
個人使用偏好 Debian 系是因為剛開始學習使用 Linux 時就是接觸 Debian, 覺得其套件管理系統 (apt-get, apt-cache, ...etc)很方便，所以就一路使用。後來參加過幾次社群活動，對於 Debian 系 distro 對於「自由軟體」的理念和堅持很認同(官方版套件庫若有一點點版權上的疑慮便不收納，即使那些套件為人所習用，ex: Firefox, Chrome)，雖然真正實行起來有困難，常常還是需要安裝 non-free 套件，但還是有點自由祟拜式地繼續使用。

