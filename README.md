# EAR
![EAR logo](https://github.com/machinelearningdays/Kilyos/blob/main/logo.png?raw=true)

EAR köpeklerin ağlamalarını tespit eden bir yapay zeka yazılımıdır.

Amacımız, bu yazılımı barınaklara, sokak kulübelerine ve evlere kurarak, köpeklerin acı çektiği anlarda yardımı hızlı ulaştırmaktır.

### Dataset
Bildiğiniz gibi her yapay zeka projesi bir veriye dayanır. Bizim de bu projede, sesleri sınıflandırmak için bir veri eğitmemiz gerekti. Verimizde hem köpeklerin ağlarken ki sesleri, hem de dış ortam veya diğer sesler gerekliydi. Bunun için internetten bulduğumuz ağlayan köpeklerin seslerini indirdik. (Bu projede hiçbir köpeğe zarar verilmemiştir).

Ağlayan köpeklerle ilgili toplam 13 video bulabildik. [(Bulduğumuz videolar)](https://docs.google.com/document/d/1ZvI9atFq-UsdVOtZ85h07mGyYKbRlZHHey4796BIXgI/edit)

Budluğumuz videoları wav formatında indirip, birer saniyelik parçalara böldük.

Eğitim datasetine [buradan](https://drive.google.com/drive/folders/1vYFczSZ53AtpR8jPxfKAEVH6NYuaCYs7?usp=sharing) ulaşabilirsiniz.

### Model Eğitimi
Modeli eğitmek için Tensorflow ve Keras kullanarak 1D bir convolutional neural network yapısı kurduk. Ardından youtube videolarında oluşturduğumuz verisetiyle bu modeli eğittik ve **%97**'lik bir başarı elde ettik.
### Gelecek Planlarımız
- Gelecek planlarımız bu eğittiğimiz modeli barınaklara ve sokak kulübelerine kurarak acı çeken köpeklerin hızlı tespitini sağlamak.
- Topladığımız verilerle geliştirdiğimiz modelin başarı skorunu arttırmak.

### Takımımız
**Özge HURMA**: Boğaziçi Üniversitesi Kimya Mühendisliği 1. sınıf öğrencisiyim. Yaklaşık bir aydır machine learning ve deep learning ile ilgileniyorum. Dans ediyorum, bisiklet sürüyorum ve dağcılık yapıyorum. Doğayı ve hayvanları seviyorum.
https://www.linkedin.com/in/%C3%B6zge-hurma-3a5b90190/

**Oktay ÖZEL**: Boğaziçi Üniversitesi Bilgisayar Mühendisliği’nde 1. sınıf öğrencisiyim. İstanbul Atatürk Fen Lisesi mezunuyum. Dağcılık ve doğa sporlarıyla ilgileniyorum. İleri seviyede İngilizce ve orta seviyede Almanca biliyorum.
https://www.linkedin.com/in/oktay-%C3%B6zel-9b3803191/

**Ekrem BAL**: Ortaokuldan beri yazılımla ilgiliyim, Lise hayatımda algoritmalarla uğraştım ve Uluslararası Bilgisayar Olimpiyatlarında ülkemizi temsilen gümüş madalya kazandım. Boğaziçi Üniversitesi Bilgisayar Mühendisliği 1. Sınıf Öğrencisiyim, aynı zamanda PragmaCraft adlı şirkette doğal dil işleme hakkında çalışıyorum.
https://www.linkedin.com/in/ekrembal 
