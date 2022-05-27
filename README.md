# GoogleMapsKotlin
Google Maps Example
- Google Maps Activity kullanılarak proje geliştirilmiştir.
- Google Cloud Platform üzerinden API Key alınmıştır.
- Link üzerinden Google Cloud Platform sayfasına ulaşabilirisiniz: [Google Cloud Platform](https://console.cloud.google.com/projectcreate?_ga=2.153696440.1895771675.1653651679-1273889845.1646821118)
- Bu API Key AndroidManifest.xml dosyasında <meta-data> etiketleri içerisine eklenmiştir.
- Kullanıcının konum bilgisine ulaşabilmek için gerekli izinler AndroidManifest.xml dosyasına eklenmiştir. Gerekli izin ekleme şekli şu şekildedir:
```
  <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
  <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
```
- Güncel konum işaretlenmesi, son konumu alma, işaretli konumun adresinin gösterilmesi işlemleri yapılmıştır.
- Projeye ait ekran görüntüleri aşağıda bulunmaktadır.
![1](https://user-images.githubusercontent.com/99657258/170789048-5dc543a5-7a21-459b-ba27-bae353672c84.png)
![2](https://user-images.githubusercontent.com/99657258/170789073-9410c52a-7e78-400c-9ac4-7b9a13f796a3.jpg)
![3](https://user-images.githubusercontent.com/99657258/170789076-f387956f-2278-489c-9d55-dbffa5686213.jpg)

  
