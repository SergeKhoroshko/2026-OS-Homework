# Завдання 1. Базові команди (1 бал)

# Покажи вміст домашнього каталогу
test@test-VirtualBox:~$ cd ~
test@test-VirtualBox:~$ ls -lah
total 108K
drwxr-x--- 15 test test 4.0K Jul  5 19:07 .
drwxr-xr-x  4 root root 4.0K Jul  5 19:00 ..
-rw-------  1 test test  473 Jul  5 19:04 .bash_history
-rw-r--r--  1 test test  220 Mar 31  2024 .bash_logout
-rw-r--r--  1 test test 3.7K Mar 31  2024 .bashrc
drwx------ 11 test test 4.0K Jul  5 16:46 .cache
drwx------ 15 test test 4.0K Jul  5 19:05 .config
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Desktop
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Documents
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Downloads
drwx------  4 test test 4.0K Jul  5 16:36 .local
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Music
-rw-r--r--  1 test test  357 Jul  5 18:50 .pam_environment
drwxr-xr-x  3 test test 4.0K Jul  5 18:41 Pictures
-rw-r--r--  1 test test  807 Mar 31  2024 .profile
drwxr-xr-x  2 test test 4.0K Jul  5 19:07 Shared
drwx------  4 test test 4.0K Jul  5 18:00 snap
drwx------  2 test test 4.0K Jul  5 16:36 .ssh
-rw-r--r--  1 test test    0 Jul  5 17:03 .sudo_as_admin_successful
-rw-rw-r--  1 test test    0 Jul  5 17:34 SVKhoroshko_homework_1.md
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Templates
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-clipboard-tty2-control.pid
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-clipboard-tty2-service.pid
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-draganddrop-tty2-control.pid
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-hostversion-tty2-control.pid
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-seamless-tty2-control.pid
-rw-r-----  1 test test    6 Jul  5 19:05 .vboxclient-vmsvga-session-tty2-control.pid
-rw-r-----  1 test test    5 Jul  5 19:05 .vboxclient-vmsvga-session-tty2-service.pid
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 Video

# Перейди у каталог Downloads і покажи його вміст
test@test-VirtualBox:~$ cd Downloads
test@test-VirtualBox:~/Downloads$ 

test@test-VirtualBox:~/Downloads$ ls -lah
total 8.0K
drwxr-xr-x  2 test test 4.0K Jul  5 16:36 .
drwxr-x--- 15 test test 4.0K Jul  5 19:07 ..

# Створи порожній файл (без touch)
test@test-VirtualBox:~/Downloads$ cat > empty_file.txt
test@test-VirtualBox:~/Downloads$ ls -lah
total 8.0K
drwxr-xr-x  2 test test 4.0K Jul  5 19:17 .
drwxr-x--- 15 test test 4.0K Jul  5 19:07 ..
-rw-rw-r--  1 test test    0 Jul  5 19:17 empty_file.txt

# Переглянь вміст файлу
test@test-VirtualBox:~/Downloads$ cat empty_file.txt
test@test-VirtualBox:~/Downloads$ 

# Перейди у домашній каталог абсолютним шляхом
test@test-VirtualBox:~/Downloads$ cd /home/test
test@test-VirtualBox:~$ 

# Перейди у домашній каталог відносним шляхом
test@test-VirtualBox:~$ cd ~
test@test-VirtualBox:~$ 

# Завдання 2. Робота з документацією
# Виконай команди:
# 1) man ls 
test@test-VirtualBox:/home$ man ls
...

# 2) help cd 
test@test-VirtualBox:/home$ help cd
cd: cd [-L|[-P [-e]] [-@]] [dir]
    Change the shell working directory.
    
    Change the current directory to DIR.  The default DIR is the value of the
    HOME shell variable. If DIR is "-", it is converted to $OLDPWD.
...

# 3) man cat 
test@test-VirtualBox:/home$ man cat
CAT(1)                                                  User Commands                                                 CAT(1)

NAME
       cat - concatenate files and print on the standard output
...

# 4) man man 
test@test-VirtualBox:/home$ man man
man: can't resolve man7/groff_man.7

MAN(1)                                               Manual pager utils                                               MAN(1)

NAME
       man - an interface to the system reference manuals
...

# 5) cp --help
test@test-VirtualBox:/home$ cp --help
Usage: cp [OPTION]... [-T] SOURCE DEST
  or:  cp [OPTION]... SOURCE... DIRECTORY
  or:  cp [OPTION]... -t DIRECTORY SOURCE...
Copy SOURCE to DEST, or multiple SOURCE(s) to DIRECTORY.
...

# 6) mv --help
test@test-VirtualBox:/home$ mv --help
Usage: mv [OPTION]... [-T] SOURCE DEST
  or:  mv [OPTION]... SOURCE... DIRECTORY
  or:  mv [OPTION]... -t DIRECTORY SOURCE...
Rename SOURCE to DEST, or move SOURCE(s) to DIRECTORY.
...

# Питання:

# 1) Який ключ ls показує приховані файли?
ls -a

# 2) Який ключ у cat нумерує рядки?
cat -n file.txt

# 3) Чим відрізняються man і -help?
--help — це швидка коротка довідка, яку сама програма виводить у термінал. Вона підходить, коли потрібно швидко згадати синтаксис або ключ.
man — це повна офлайн-документація. Вона відкриває man-сторінку з детальним описом команди, її синтаксису, опцій і прикладів.

# Завдання 3. Міні-сценарій (2 бали)

# Склади сценарій із 6–10 команд, який дозволить:

# Перейти в каталог
# Створити там один файл
# Переглянути список файлів
# Перейти в інше місце
# Повернутись назад
# Переглянути документацію однієї з команд
# Важливо: сценарій повинен використовувати тільки ті команди, які вивчені у темах 1-5.

# Міні-сценарій
cd ~
cd Downloads
cat > homework_file.txt
ls -lah
cd ..
pwd
cd -
man cat

# End /SVKhoroshko_homework_1.md
