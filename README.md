# Veri Test
 Arabam.com sitesinden alınan verilerle nissan marka araçların fiyat tahmini ile regresyon algoritmalarının kıyaslaması 
 
 ## Projenin Çalısması için Gerekeneler
 - Anaconda Individual Edition ve Jupyter Notebook
 - Beautifulsoup kütüphanesi
   #### Beautifulsoup kütüphanesi yüklemek
    - Anaconda Navigator ile Cmd veya powershell prompt açılır
    - Çıkan konsola ``` pip install beautifulsoup4 ``` yazılır ve enter a basılır pip otomatik olarak beatifulsoup kütüphanesini ekler
    - Requests kütüphanesi yoksa gene konsola  ``` pip install requests ``` yazılarak kütüphane yüklenir
## Proje Nasıl Çalıştırılır ve Kullanılan Teknolojiler

Projeyi çalıştırmak için özel birşey gerekmemektedir. Veri Çekme kısmı için ``` webscrapper.ipynb ``` dosyasını çalıştırınız. Veriyi düzenleme ve fiyat tahmin kısmı için ```proses.ipynb``` dosyasını çalıştırınız. Projeyi düzenelenerek başka sitelerden veri çekme işlemlerinde kullanabilirsiniz.
- Projede Python dili kullanılmıştır. 
- Derleyici olarak Jupyter Notebook kullanılşmıştır.
- Requests kütüphanesi ile sitelere html istekleri atılması sağlanmıştır
- Beautifulsoup kütüphanesi sayesinde sitelerden html kodlarını kullanarak veri çekme işlemi yapılmıştır.
- Pandas kütüphanesi sayesinde dataframeler sayesinde daha anlaşılır bir şekilde saklanmıştır
- Matplotlib pyplot kütüphanesi verileri görselleştirmek için kullanılmıştır
- Scikit-learn kütüphanesi verileri test ve train olarak ayırmak ve regresyon algoritmalarını kullanmak için kullanılmıştır

