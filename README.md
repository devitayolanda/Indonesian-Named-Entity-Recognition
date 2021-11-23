Kelompok Kraken Proyek PBA

Judul:<br>
Indonesian Named Entity Recognition Menggunakan NN dan Bi-LSMP

**A. Latar Belakang**<br>
Menurut KBBI, dokumen merupakan kumpulan text yang bertujuan untuk memberikan informasi ataupun bukti yang digunakan/dimanfaatkan dalam berbagai macam hal. Dokumen yang berisikan text tersebut tentunya memiliki berbagai macam jenis kata didalamnya. Berbagai jenis kata tersebut dapat berupa, kata benda, kata kerja, kata keterangan, dan lain sebagainya. Dengan berbagai jenis tersebutlah maka terbentuk sebuah pembelajaran yang membantu dalam melakukan klasifikasi kata-kata yang terdapat pada dokumen tersebut. Pembelajaran yang dapat digunakan dalam klasifikasi kata adalah Named Entity Recognition (NER) dengan tujuan untuk mendapatkan informasi penting dengan cepat dan akurat dalam proses pemecahan sederhana, efektif dan efisien.<br>
Named entity recognition (NER) merupakan bagian atau tugas dari pemrosesan bahasa alami (NLP) yang bertujuan untuk mengidentifikasi atau mengklasifikasikan suatu entitas. Entitas yang dimaksud dapat berupa nama orang, organisasi, waktu, lokasi, dan nama-nama entitas lain dalam teks. NER ini juga dapat digunakan dalam situasi pemrosesan bahasa alami lainnya, seperti halnya ekstraksi informasi dan pembuatan kueri otomatis. Model NER pertama-tama mengidentifikasi suatu entitas dan kemudian mengkategorikan entitas tersebut ke dalam kelas yang paling sesuai. Seiring dengan kemajuan teknologi, model NER ini semakin maju sehingga kita ketahui bahwa model NER ini bahkan sudah dimanfaatkan dalam membantu sistem besar seperti Google Translate dan lain sebagainya. Dari hal tersebut dikatakan bahwa penggunaan NER ini merupakan pembelajaran yang bermanfaat dalam berbagai bidang. NER juga dapat digunakan diberbagai tujuan untuk mengetahui berbagai bentuk bahasa yang akan diekstraksi menjadi suatu informasi yang berguna untuk mewakili suatu kata yang mudah dikenali oleh manusia. Dalam pengimplementasiannya juga terdapat berbagai cara yang dilakukan dalam pembangunan pendekatan model dalam NER. Beberapa algoritma yang sudah pernah dilakukan adalah Naive Bayes, ANN, CRF dan lain sebagainya. <br>
Pada proyek ini, hal yang akan dilakukan oleh penulis adalah bagaimana melakukan pembentukan model sederhana dalam menerapkan NER dengan menggunakan salah satu algoritma pada machine learning yaitu Neural Network. Adapun alasan penulis memilih algoritma Neural Network dalam klasifikasi NER dikarenakan pada pendekatan neural network sistem akan secara otomatis mempelajari dan mengenali pola komponen dan membuat keputusan cerdas berdasarkan data yang tersedia. Dengan kelebihan yang dimiliki ini, algoritma Neural Network ini juga dimanfaatkan dalam melakukan ekstraksi Feature yang juga merupakan bagian dari proses NER yang akan dilaksanakan. Algoritma ini akan melakukan klasifikasi informasi baru dalam data yang terdapat pada database sehingga membantu dalam pembentukan model yang akan dihasilkan. Pada pembentukan model sendiri penulis akan menggunakan layer Bi-LSTM yang digunakan untuk memecahkan masalah NER dalam dokumen berbahasa indonesia yang akan digunakan. 
<br>Seperti yang kita tahu aturan umum pada sebuah kalimat bahasa indonesia adalah : S + P + O. Oleh karena itu pada pembentukan model yang dilakukan dengan memanfaatkan NN dan Bi-LSTM, model tersebut akan membantu dalam melakukan klasifikasi kata-kata yang terdapat pada kalimat, dan mencegah ambiguitas sebuah kata yang memiliki pengertian lebih dari satu. 
<br>. Sehingga ketika melakukan pemasukan input akan model yang dibentuk, model akan berhasil melakukan klasifikasi berbagai jenis kata yang dimasukkan dengan memanfaatkan dataset yang telah diklasifikasi sebelumnya. 


**B. Dataset**

Data yang digunakan adalah dataset berbahasa indonesia (dataset 
SINGGALANG)

[SINGGALANG.csv](https://github.com/devitayolanda/Indonesian-Named-Entity-Recognition/files/7561381/SINGGALANG.csv)

**C. Evaluasi : Confussion Matrix <br>**

**D.Preprocessing : Word2Vec <br>**

**E. Metode : Bi-lstm <br>**
Bidirectional LSTM menggabungkan
konteks sebelumnya dan konteks setelahnya dengan
memproses data dari dua arah yang selanjutnya
diklasifikasi menggunakan CRF.

Dalam metode pembelajaran
mesin terdapat metode yang terbukti mendapatkan
pencapaian performa paling tinggi(state-of-the-art)
dalam kasus NER [3], yaitu Bidirectional LSTMCRF

**F. Feature ekstraksi : Neural Network**
