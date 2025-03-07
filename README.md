**ssh key orqali access qilish uchun qaysi serverdan ulanmoqchi bo'lsa usha serverda ssh-key generatsiya qilinadi. Keyin qilinga public keyni qaysi serverga ulanmoqchi bo'lsa usha serverga copy qiladi.**

**.ssh-key ssh keyni genaratsiya qilish**
     
     ssh-keygen -t rsa

     root@kubectl:~#cd .ssh

**Yasalgan public-keyni(id_rsa.pub) qaysi serverga ssh access qilmoqchi bo'lsa usha serverga copy qilinadi va password so'raganda usha qaysi serverga ulanmoqchi bo'lsa usha server passworddi teriladi.**
     
     ssh-copy-id user@192.168.151.10

**Keyin login ip bilan ssh orqali ulaniladi**

     ssh user@192.168.151.10
