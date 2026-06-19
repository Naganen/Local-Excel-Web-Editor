# Excel Web Düzenleyici (Excel Web Editor)

https://naganen.github.io/Local-Web-Excel-Editor/

Excel Tarayıcı Düzenleyici, Excel dosyalarınızı doğrudan tarayıcınız üzerinden yönetmenizi sağlayan, kurulum gerektirmeyen ve tamamen yerel çalışan bir web uygulamasıdır. Dosyalarınızı ve içlerindeki çalışma sayfalarını (worksheets) kolayca listelemenize, verileri düzenlemenize ve veri tiplerini yönetmenize olanak tanır.

## 🚀 Öne Çıkan Özellikler

* **Yerel Çalışma (Local-First):** Verileriniz asla internete yüklenmez. Tüm işlemler tarayıcınızın kendi gücüyle yapılır, bu sayede verileriniz %100 güvendedir.
* **Hiyerarşik Gezinti:** Birden fazla Excel dosyasını sisteme ekleyebilir, sol taraftaki menü üzerinden dosyaları ve içerisindeki çalışma sayfalarını kolayca yönetebilirsiniz.
* **Dinamik Veri Düzenleme:**
* Hücreleri doğrudan tablo üzerinde düzenleyin.
* Hücrelerin veri tiplerini (Metin, Sayı, Tarih, Mantıksal) anlık olarak değiştirin.
* Veri tipine göre otomatik uyum sağlayan giriş alanları ile hata payını düşürün.


* **Yapısal Kontrol:** İhtiyacınıza göre kolayca satır ve sütun ekleyip çıkarabilirsiniz.
* **Dışa Aktarma:** Yaptığınız tüm değişiklikleri orijinal Excel formatında bilgisayarınıza geri indirebilirsiniz.

## 🛠 Kullanılan Teknolojiler

* **HTML5/CSS3:** Tailwind CSS ile oluşturulmuş modern ve duyarlı arayüz.
* **JavaScript (Vanilla):** Dosya işleme ve veri yönetimi için optimize edilmiş temiz kod yapısı.
* **SheetJS (xlsx):** Excel dosyalarını okuma ve yazma işlemlerinde endüstri standardı kütüphane.
* **Lucide Icons:** Modern ve şık simge seti.

## 📦 Nasıl Kullanılır?

1. **Dosyayı Açın:** Proje dosyalarınızı indirin ve `index.html` dosyasını favori web tarayıcınızda (Chrome, Firefox, Edge) açın.
2. **Yükleme:** Excel dosyalarınızı uygulama içerisindeki yükleme alanına sürükleyip bırakın.
3. **Düzenleme:**
* Sol menüden bir dosya ve ardından bir çalışma sayfası seçin.
* Bir hücreyi düzenlemek için üzerine çift tıklayın, değerini ve veri tipini güncelleyin.
* Araç çubuğunu kullanarak satır/sütun ekleme veya silme işlemlerini gerçekleştirin.


4. **Kaydetme:** "İndir" butonuna tıklayarak yaptığınız değişikliklerle birlikte dosyayı bilgisayarınıza kaydedin.

## 📋 Proje Yapısı

```text
/
└── index.html       # Ana uygulama arayüzü ve tüm mantık

```

## ⚠️ Önemli Notlar

* **Veri Gizliliği:** Uygulama tüm işlemlerini istemci tarafında (tarayıcınızda) gerçekleştirir. Hiçbir veriniz sunucuya gönderilmez.
* **Tarayıcı Desteği:** En iyi performans ve özellik uyumluluğu için güncel bir web tarayıcısı kullanmanız önerilir.

## 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz.
