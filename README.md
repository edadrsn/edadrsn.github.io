# Eda Dursun — Portföy

HTML, CSS ve JavaScript ile hazırlanmış kişisel portföy sitesi. Derleme veya paket kurulumu gerekmez.

## Yerelde çalıştırma

Bu klasörde bir terminal açın:

```sh
python -m http.server 8090 --bind 127.0.0.1
```

Tarayıcıda http://127.0.0.1:8090 adresini açın.

## Dosyalar

- `index.html`: Ana sayfa ve statik içerik.
- `style.css`: Duyarlı tasarım, açık/koyu tema.
- `app.js`: Projeler, detay pencereleri, filtreler, dil ve tema kontrolleri.
- `assets/`: Belgeden alınan ürün görselleri, Coffee House ekran görüntüleri ve Türkçe/İngilizce CV.

Projeler ve açıklamaları `app.js` içindeki `projects` listesinde düzenlenir. İngilizce arayüz metinleri `translations` nesnesindedir; Türkçe arayüz metinleri HTML içindedir.

Uygulama tanıtım görselleri, kullanıcı tarafından verilen Word belgesinden alınmıştır. Bu görseller ürün düzeyindedir; Android ekranlarının birebir görüntüsü olduğu iddia edilmez. RentACar mimari şeması hedeflenen yapıyı temsil eder. Proje katkıları ve deneyim bilgileri kullanıcının sağladığı belgeden düzenlenmiştir.

Google Fonts çevrimiçi yüklenir; bağlantı olmadığında sistem yazı tipleri kullanılır. Diğer arayüz varlıkları yereldir. Site henüz yayınlanmamıştır.
