# CV
Computer Vision - Bilgisayarli Goru
# Yüz Tanıma (Face Recognition) :girl: :boy: :child:

Gerekli kurulumları yaptıktan sonra Anaconda üzerinde, Jupyter Notebook ile kodlar yazılabilir. 

Anaconda Prompt üzerinde Python kullanarak PyTorch Kütüphanesini import ettikten sonra GPU’nun kullanılabilir olduğunu test ettim. 

![image](https://user-images.githubusercontent.com/82284108/145257384-a222dabf-8cc7-47d9-8103-ec4819bd0ef8.png)


BTK Akademi'de bulanan 'Bilgisayarlı Görü Uygulama Alanları' kursundan 'ArcFace ile Yüz Tanıma' video serisinden yararlandım.


**ArcFace** veya Additive Angular Margin Loss modeli; yüz tanıma, yüz arama işlemleri için kullanılabilir.

Eğitim(train) veri seti olarak MS1M veri seti kullanıldı. Veriler, veri setinde klasörlere ayrılmış olarak bulunmaktadır.

![image](https://user-images.githubusercontent.com/82284108/145257915-6da483e0-f515-47bd-8679-423f79d0884a.png)

“0” klasörüne ait örnek görüntüler aşağıda görülmektedir.

![image](https://user-images.githubusercontent.com/82284108/145258113-aab8f507-493f-4283-a0e1-8d1c9043ff74.png)

Proje "Yuz_Tanima.ipynb" içerisinde bulunmaktadir.

>Derin Öğrenme için Pytorch kurulumunda, eğitimi GPU kullanarak yapmak için aşağıda kaynaklar kullanılabilir:
>
>https://www.youtube.com/watch?v=U0i7-c3Vrgc&list=PLZoTAELRMXVNxYFq_9MuiUdn2YnlFqmMK&index=3
>
>https://sh-tsang.medium.com/tutorial-cuda-cudnn-anaconda-jupyter-pytorch-installation-in-windows-10-96b2a2f0ac57





