<!--! Git hub blan ishlash v akerakliy qo'dlar -->

1- git init - bu orqaliy git hubni o'zimizga yuklaymiz va yangi repositoriy yaratishimiz mumkun

2- git add . - bunda yangi fayillayni qo'shganda ishlatilinadi

3- git commit -m "first" - bu Git buyrug'i bo'lib, staging area (oldin git add bilan tayyorlangan fayllar) dagi barcha o'zgarishlarni yangi commit sifatida saqlaydi. Bu commitni sizning loyihangiz tarixiga qo'shadi va u bilan bog'liq biror sharh yozadi.

4- Branch nomini o'zgartirish Bu buyruq joriy branchning (shoxcha) nomini "master" ga o'zgartiradi.
Agar joriy branchning nomi boshqacha bo'lsa (masalan, main), u endi master deb nomlanadi.

5- git push -u origin master - bu Git buyrug‘i bo‘lib, u lokal branch (master) ni masofaviy repository (origin) ga yuborish uchun ishlatiladi. Shuningdek, bu buyruq lokal branchga masofaviy branch bilan bog‘lanishni o‘rnatadi, shunda keyinchalik git push va git pull buyruqlarini qisqa shaklda ishlatish mumkin bo‘ladi.

6- git checkout -b husan - bu Git buyrug‘i bo‘lib, u yangi branch yaratish va shu branchga o‘tish uchun ishlatiladi.

<!--! push 1ilish uchun -->

1 - git add .
2 - git commit -m "second"
