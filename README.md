<h1 align="center"> NLP With Hugging Face Transformers </h1>
<p align="center"> Berisi tentang pipeline dari Hugging Face Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>
<h2 align="center"> ANALISIS </h2>

HuggingFace Transformers NLP Pipelines

1. Zero-shot Classification  
   Zero-shot classification adalah teknik dalam pemrosesan Natural Language Processing yang memungkinkan model untuk mengklasifikasikan teks ke dalam kategori tertentu tanpa pelatihan khusus pada kategori tersebut sebelumnya. Dalam metode ini, model dapat mengenali dan memahami konteks atau maksud dari teks hanya berdasarkan prompt atau deskripsi sederhana tentang kategori yang diinginkan. Pipeline ini termasuk dalam **klasifikasi teks** dan sangat berguna dalam situasi di mana kategori baru sering muncul, karena model dapat mengidentifikasi relevansi teks dengan kategori berdasarkan deskripsi yang diberikan. Aplikasinya meliputi analisis berita dan pengkategorian konten dinamis di media sosial.

2. Text Generation  
   Text generation adalah teknik dalam pemrosesan bahasa alami yang memungkinkan model menghasilkan teks secara otomatis berdasarkan prompt atau masukan tertentu. Dalam text generation, model akan melanjutkan kalimat atau menyusun paragraf secara kontekstual, mencoba membuat teks yang koheren dan relevan dengan topik yang diinginkan. Pipeline ini termasuk dalam pembuatan konten dan bermanfaat dalam pembuatan konten otomatis, dialog, dan penyusunan paragraf. Contoh aplikasinya adalah dalam chatbot, alat pembuatan artikel, dan penulisan kreatif.

3. Fill-mask  
   Fill-mask adalah teknik dalam pemrosesan bahasa alami yang memungkinkan model untuk mengisi kata yang hilang atau kosong dalam sebuah kalimat dengan kata yang paling cocok berdasarkan konteks. Teknik ini sering digunakan untuk melatih model memahami makna kata dalam konteks yang lebih luas. Pipeline ini termasuk dalam pemahaman bahasa dan memperdalam pemahaman model tentang hubungan antar kata dalam kalimat. Ini sering digunakan dalam pendidikan dan pelatihan model bahasa untuk memperkenalkan kosakata baru kepada pengguna.

4. Named Entity Recognition (NER) 
   NER atau Named Entity Recognition adalah teknik dalam pemrosesan bahasa alami yang digunakan untuk mengidentifikasi dan mengkategorikan entitas bernama dalam teks, seperti nama orang, organisasi, lokasi, tanggal, angka, dan lainnya. Dengan NER, model dapat menyoroti bagian-bagian penting dari teks yang memiliki makna khusus dan menempatkannya ke dalam kategori yang sesuai. Pipeline ini termasuk dalam ekstraksi informasi dan sangat berguna dalam analisis dokumen, pengolahan data besar, dan pencarian informasi penting dari teks panjang, mempermudah pemahaman konteks.

5. Question Answering 
   Question answering adalah teknik dalam pemrosesan bahasa alami yang memungkinkan model untuk menjawab pertanyaan secara langsung berdasarkan konteks atau sumber teks yang diberikan. Dalam question answering, model menerima pertanyaan dan teks atau konteks terkait, kemudian memberikan jawaban yang relevan, sering kali dengan pemahaman yang mendekati cara manusia merespons. Pipeline ini termasuk dalam interaksi teks dan meningkatkan pengalaman pengguna dalam berkomunikasi dengan mesin, membuatnya ideal untuk aplikasi seperti chatbot dan sistem pencarian informasi.

6. Sentiment Analysis 
   Sentiment analysis adalah teknik dalam pemrosesan bahasa alami yang digunakan untuk mengidentifikasi dan mengklasifikasikan emosi atau perasaan dalam teks, seperti positif, negatif, atau netral. Teknik ini membantu memahami opini, reaksi, atau perasaan seseorang terhadap suatu topik berdasarkan kata-kata atau frasa yang digunakan dalam teks. Pipeline ini termasuk dalam analisis emosi dan berguna untuk memahami opini masyarakat, menganalisis ulasan produk, dan memantau reaksi pengguna terhadap berbagai topik di media sosial.

7. Summarization 
   Summarization adalah teknik dalam pemrosesan bahasa alami yang digunakan untuk meringkas teks panjang menjadi versi yang lebih pendek, sambil tetap mempertahankan informasi utama dan esensi dari teks asli. Model summarization akan membaca keseluruhan teks dan memberikan rangkuman singkat yang mudah dipahami tanpa kehilangan konteks penting. Pipeline ini termasuk dalam penyajian informasi dan membantu pengguna memahami inti dari dokumen yang panjang dengan cepat, sangat berguna dalam meringkas laporan, artikel, dan dokumen penelitian.