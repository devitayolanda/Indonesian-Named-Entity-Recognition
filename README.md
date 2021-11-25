Kelompok Kraken Proyek PBA

Judul:<br>
Indonesian Named Entity Recognition Menggunakan NN dan Bi-LSMP

**A. Latar Belakang**<br>
Menurut KBBI, dokumen merupakan kumpulan text yang bertujuan untuk memberikan informasi ataupun bukti yang digunakan/dimanfaatkan dalam berbagai macam hal. Dokumen yang berisikan text tersebut tentunya memiliki berbagai macam jenis kata didalamnya. Berbagai jenis kata tersebut dapat berupa, kata benda, kata kerja, kata keterangan, dan lain sebagainya. Dengan berbagai jenis tersebutlah maka terbentuk sebuah pembelajaran yang membantu dalam melakukan klasifikasi kata-kata yang terdapat pada dokumen tersebut. Pembelajaran yang dapat digunakan dalam klasifikasi kata adalah Named Entity Recognition (NER) dengan tujuan untuk mendapatkan informasi penting dengan cepat dan akurat dalam proses pemecahan sederhana, efektif dan efisien.<br>
Named entity recognition (NER) merupakan bagian atau tugas dari pemrosesan bahasa alami (NLP) yang bertujuan untuk mengidentifikasi atau mengklasifikasikan suatu entitas. Entitas yang dimaksud dapat berupa nama orang, organisasi, waktu, lokasi, dan nama-nama entitas lain dalam teks. NER ini juga dapat digunakan dalam situasi pemrosesan bahasa alami lainnya, seperti halnya ekstraksi informasi dan pembuatan kueri otomatis. Model NER pertama-tama mengidentifikasi suatu entitas dan kemudian mengkategorikan entitas tersebut ke dalam kelas yang paling sesuai. Seiring dengan kemajuan teknologi, model NER ini semakin maju sehingga kita ketahui bahwa model NER ini bahkan sudah dimanfaatkan dalam membantu sistem besar seperti Google Translate dan lain sebagainya. Dari hal tersebut dikatakan bahwa penggunaan NER ini merupakan pembelajaran yang bermanfaat dalam berbagai bidang. NER juga dapat digunakan diberbagai tujuan untuk mengetahui berbagai bentuk bahasa yang akan diekstraksi menjadi suatu informasi yang berguna untuk mewakili suatu kata yang mudah dikenali oleh manusia. Dalam pengimplementasiannya juga terdapat berbagai cara yang dilakukan dalam pembangunan pendekatan model dalam NER. Beberapa algoritma yang sudah pernah dilakukan adalah Naive Bayes, ANN, CRF dan lain sebagainya. <br>
Pada proyek ini, hal yang akan dilakukan oleh penulis adalah bagaimana melakukan pembentukan model sederhana dalam menerapkan NER dengan menggunakan salah satu algoritma pada machine learning yaitu Neural Network. Adapun alasan penulis memilih algoritma Neural Network dalam klasifikasi NER dikarenakan pada pendekatan neural network sistem akan secara otomatis mempelajari dan mengenali pola komponen dan membuat keputusan cerdas berdasarkan data yang tersedia. Dengan kelebihan yang dimiliki ini, algoritma Neural Network ini juga dimanfaatkan dalam melakukan ekstraksi Feature yang juga merupakan bagian dari proses NER yang akan dilaksanakan. Algoritma ini akan melakukan klasifikasi informasi baru dalam data yang terdapat pada database sehingga membantu dalam pembentukan model yang akan dihasilkan. Pada pembentukan model sendiri penulis akan menggunakan layer Bi-LSTM yang digunakan untuk memecahkan masalah NER dalam dokumen berbahasa indonesia yang akan digunakan. Bi-lstm ini secara efektif meningkatkan jumlah informasi yang tersedia untuk jaringan dan meningkatkan konteks yang tersedia untuk algoritma
<br>Seperti yang kita tahu aturan umum pada sebuah kalimat bahasa indonesia adalah : S + P + O. Oleh karena itu pada pembentukan model yang dilakukan dengan memanfaatkan NN dan Bi-LSTM, model tersebut akan membantu dalam melakukan klasifikasi kata-kata yang terdapat pada kalimat. Sehingga ketika melakukan pemasukan input akan model yang dibentuk, model akan berhasil melakukan klasifikasi berbagai jenis kata yang dimasukkan dengan memanfaatkan dataset yang telah diklasifikasi sebelumnya. 


**B. Dataset**

Data yang digunakan adalah dataset berbahasa indonesia (dataset 
SINGGALANG)

[SINGGALANG.csv](https://github.com/devitayolanda/Indonesian-Named-Entity-Recognition/files/7561381/SINGGALANG.csv)

**C. Evaluasi : Confussion Matrix <br>**
Confusion matrix sering disebut sebagai error matrix. Dimana, pada dasarnya confusion matrix akan memberikan informasi dari perbandingan hasil klasifikasi yang dilakukan oleh sistem (model) dengan hasil klasifikasi sebenarnya. Confussion matrix digunakan agar dapat memberi tahu seberapa baik model yang telah dibuat.

**D.Preprocessing : Word2Vec <br>**

**E. Metode : Bi-lstm <br>**
Bidirectional LSTM, atau biLSTM, adalah model pemrosesan urutan yang terdiri dari dua LSTM: satu mengambil input dalam arah maju, dan yang lainnya dalam arah mundur. 
BiLSTM secara efektif meningkatkan jumlah informasi yang tersedia untuk jaringan, meningkatkan konteks yang tersedia untuk algoritme (misalnya, mengetahui kata apa yang segera mengikuti dan mendahului kata dalam kalimat).

**F. Feature ekstraksi : Neural Network <br>**
Feature Ekstraksi adalah proses pengambilan ciri objek yang dapat menggambarkan atau menjelasakan karakteristik mengenai objek tersebut. Pada Feature Extraksi data yang ada akan menjadi relevan dan terstruktur. Feature extraksi mengurangi resource untuk menggambarkan kumpulan data yang besar. Neural Network merupakan suatu algoritma dalam MAchine Learning yang memiliki kemampuan untuk meyaring sejumlah informasi yang besar dari berbagai bentuk data, mengekstraksi fitur dan juga memiliki kemampuan pengklasifikasian yang kuat.

**G. Rumusan Masalah <br>**
Berdasarkan latar belakang masalah maka dapat diperoleh rumusan masalah, yaitu bagaimana membangun model Named Entity Recognition (NER) dengan menggunakan Neural Network.


** Tujuan<br>**
Untuk membangun model Named Entity Recognition (NER) pada dataset
bahasa indonesia menggunakan neural network.

**Ruang Lingkup <br>**
1. Data yang digunakan adalah dataset berbahasa indonesia (dataset
SINGGALANG)
