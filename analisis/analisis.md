## ANALISIS 
Dataset diperoleh dari link https://github.com/SebinDuke/Sentiment-Analysis-of-songs-by-lyrics/tree/master/FullDataSet. Dataset tersebut merupakan kumpulan lirik lagu dalam bahasa inggris yang terdiri dari 400 lagu untuk train data dan 378 lagu untuk test data. Dataset diperoleh dalam format file .csv. Setiap record data diberikan label angry, happy, relaxed, dan sad. Atribut (Feature) yang terdapat pada dataset antara lain:

    1.SongID: SongID merupakan ID dari setiap lagu (song) yang merupakan nilai unik.
    2.Song Name: SongName merupakan judul dari lagu tersebut
    3.Artist’s Name: Artist’s Name merupakan nama artis yang menyanyikan lagu tersebut.
    4.Duration of Music (seconds): Duration of Music merupakan durasi lagu tersebut dalam satuan detik.
    5.Category: Category merupakan label dari setiap lirik lagu, yaitu terdapat category angry, happy, relaxed, dan sad.
    6.Lyrics: Lyrics merupakan lirik dari lagu tersebut.
Atribut (Feature) yang digunakan untuk melakukan analisis sentimen lirik lagu adalah : 

    1.Lyrics
    2.Category
Untuk melakukan analisis sentimen lirik lagu pada Spotify ini digunakan algoritma SVM. SVM merupakan salah satu metode dalam supervised learning yang digunakan untuk klasifikasi.
Dalam SVM, untuk memisahkan data terhadap kelasnya, SVM akan membangun sebuah hyperplane (bidang pemisah).
