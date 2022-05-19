# DEVOPS

## Real Life Problem

### Tanpa DevOps

Team Dev ingin merilis suatu aplikasi ke Production, Team Dev menyerahkan code ke Team Ops untuk merilis aplikasi tersebut.

Team Ops akan merilis and memonitor aplikasi tersebut ke production.

Jika ada masalah di aplikasi tersebut, Team Ops harus memberitahu Team Dev tentang issuenya, lalu Team Dev akan memperbaiki dan menyerahkan kembali code tersebut kepada Team Ops untuk dideploy kembali.

Dev > Ops | (issue) | Ops > Dev | (Bug Fixing) | Dev > Ops ....

### Dengan DevOps

Role antara Dev and Ops dapat melebur, sehingga setiap team member memiliki kemampuan untuk menulis aplikasi, merilis nya ke production, memonitor dan memaintainnya.

Dev (Issue) | (Bug Fixing) | (Deploy) | (Monitoring)

## INTRO

![DevOps Culture](https://martinfowler.com/bliki/images/devOpsCulture/devops_culture.png)

### Organization Culture

#### No Silos

Budaya DevOps menyamarkan pemisah antara tugas seorang developer dan oprasional.

Anti-Pattern yang umum terjadi adalah memberikan role DevOps kepada seseorang atau team, hal tersebut akan counter-intuitive karena menciptakan Silo baru dan mempersulit budaya DevOps untuk diadopsi secara umum didalam organisasi.

#### Autonomous Teams

Dalam budaya DevOps setiap anggota team diberikan otonomi untuk mengambil keputusan dan menerapkannya.

### Team Culture

#### Shared Responsibility

> With Great Responsibility Comes Great Power - Reverse Spiderman.

Shared Responsibility merupakan aspek inti pada budaya DevOps, hal ini dibutuhkan untuk menghilangkan Silo antar team.

_Sense of Ownership_ terhadap aplikasi atau service dapat terbangun ketika suatu team diberikan tanggung jawab untuk membuat dan merawat aplikasi tersebut.

#### Build Quality In

Dengan budaya DevOps setiap anggota team dapat dengan mudah merilis aplikasinya ke production, maka kualitas dari setiap rilis harus sangat diperhatikan. Untuk menjaga kualitasnya diperlukan perubahan budaya yang lebih dalam, seperti dengan menerapkan TDD dan CI/CD yang membuat setiap rilis menjadi reguler dan beresiko rendah.

#### Feedback

Budaya DevOps sangat menghargai feedback. Karena rilis dapat dilakukan secara reguler, memonitor bagaimana aplikasi berjalan di production pada setiap rilis dapat sangat membantu feedback-loop untuk menemukan potensi improvment atau untuk mendiagnosa suatu issue.

#### Automation

Automation adalah suatu pilar penting untuk memfasilitasi kolaborasi. Pekerjaan yg repetitif dan memobosankan seperti testing dan deployment dapat diautomasi sehingga anggota team dapat fokus kepada hal lain yang lebih penting dan probabilitas human-error lebih berkurang.
