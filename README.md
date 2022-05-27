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
  
