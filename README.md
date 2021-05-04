# Veri Çekme Test
 Sahibinden sitesinden mazda marka arabalarla veri çekme ve düzenleme ile ilgili bir deneme projesi
## Başlamadan Önce
 #### Sahibinden sitesinde yapılan güncelleme yüzünden artık bu projede kullanılan yöntem ile veri çekilme yapılamamaktadır. Ama benzer bir şekilde biraz web scraping ile başka sitelerden veri çekilebilir
 ## Projenin Çalısması için Gerekeneler
 - Anaconda Individual Edition ve Jupyter Notebook
 - Beautifulsoup kütüphanesi
   #### Beautifulsoup kütüphanesi yüklemek
    - Anaconda Navigator ile Cmd veya powershell prompt açılır
    - Çıkan konsola ``` pip install beautifulsoup4 ``` yazılır ve enter a basılır pip otomatik olarak beatifulsoup kütüphanesini ekler
    - Requests kütüphanesi yoksa gene konsola  ``` pip install requests ``` yazılarak kütüphane yüklenir
## Proje Nasıl Çalıştırılır ve Kullanılan Teknolojiler

Projeyi çalıştırmak için özel birşey gerekmemektedir. Veri Çekme kısmı için ``` webscrapper.ipynb ``` dosyasını çalıştırınız. Veriyi düzenleme kısmı için ```prepro.ipynb``` dosyasını çalıştırınız. Projeyi düzenelenerek başka sitelerden veri çekme işlemlerinde kullanabilirsiniz.
- Projede Python dili kullanılmıştır. 
- Derleyici olarak Jupyter Notebook kullanılşmıştır.
- Requests kütüphanesi ile sitelere html istekleri atılması sağlanmıştır
- Beautifulsoup kütüphanesi sayesinde sitelerden html kodlarını kullanarak veri çekme işlemi yapılmıştır.
- Pandas kütüphanesi sayesinde dataframeler sayesinde daha anlaşılır bir şekilde saklanmıştır
- Openpyxl kütüphanesi sayesinde verileri yeni bir excel dosyasını yada daha önce olan bir excel dosyasına yazılması sağlanmıştır
