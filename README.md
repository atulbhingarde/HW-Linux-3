root@cyber-security-ubuntu:~/Projects# rm -rf Projects 
root@cyber-security-ubuntu:~/Projects# cp /home/student/Projects/TarDocs.tar
cp: missing destination file operand after '/home/student/Projects/TarDocs.tar'
Try 'cp --help' for more information.
root@cyber-security-ubuntu:~/Projects# cp /home/student/Projects/TarDocs.tar . 
root@cyber-security-ubuntu:~/Projects# tar -tvf TarDocs.tar | grep test | grep txt$
root@cyber-security-ubuntu:~/Projects# tar -uvf TarDocs.tar test1.txt test2.txt
test1.txt
test2.txt
root@cyber-security-ubuntu:~/Projects# tar -tvf TarDocs.tar | grep test | grep txt$
-rw-r--r-- root/root         7 2019-10-31 16:17 test1.txt
-rw-r--r-- root/root         6 2019-10-31 16:17 test2.txt
root@cyber-security-ubuntu:~/Projects# 

# HW-Linux-3
test
HW-Linux-3
