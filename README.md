# 📚 Ders Programı (C# WinForms)

Bu proje, öğrencilerin haftalık ders programlarını kolayca takip edebilmeleri için geliştirilen bir masaüstü uygulamadır. Microsoft Visual Studio kullanılarak C#, SQL ve .NET Framework ile geliştirilmiştir.

---

## 🖥️ Özellikler

- 📅 Haftalık ders saatlerini girme ve görüntüleme
- 📊 Rapor sayfası (Derslik bazlı analiz veya listeleme)
- 🪟 Kullanıcı dostu WinForms arayüzü
- 💾 Dataset üzerinden veri yönetimi

---

## 🔧 Gereksinimler

- [Visual Studio 2019 veya üzeri](https://visualstudio.microsoft.com/)
- .NET Framework 4.x (Proje ayarına göre)
- Veritabanı olarak SQL Server Management Studio Management Studio 19 kullanmıştım.
- Visual Studio eklentisi olarakta "Microsoft RDLC Report Designer" eklenmeli (bunu eklemek yerine Ders Programı pencersinde olan kaydet kısmını çıkartabilirsiniz.)

---

## 🚀 Nasıl Çalıştırılır

1. Bu projeyi GitHub'dan klonlayın veya ZIP olarak indirin:
   ```bash
   git clone https://github.com/affangul/Ders-Program-
2. Visual Studio ile Ders Programı.sln dosyasını açın.

3. Gerekirse .NET Framework hedefini güncelleyin.

4. Yüklenen dosyalar içinden DersProgrami.bak dosyasını veritabanına ekleyin.

5. Program.cs dosyasındaki veritabanı bağlantı kısmına kendi bağlantı bilginizi ekleyin.

6. "Başlat" tuşuna basarak uygulamayı çalıştırın.

7. Veritabanına önceden eklenmiş olan admin hesabıyla giriş yapın.

8. Bilgi düzenleme penceresini açarak ders programı için gerekli bilgileri ekleyin. Takip edilmesi gereken sıra:
Derslik (önce Derslik Türü, sonra Derslik İsmi) → Öğretmen → Müfredat → Sınıf → Ders
(İlk kullanımda bu sıraya göre veri girişleri yapılması daha verimli olur.)

9. "Ders Programı Oluştur" tuşuna basın. Açılan pencerede derslerin yapılacağı saatleri ve günleri seçin, ardından tekrar "Ders Programı Oluştur" tuşuna tıklayın.

10. Ders Programı penceresini açtığınızda sınıflara, dersliklere ve öğretmenlere göre günlere ayrılmış şekilde programın otomatik sıralandığını göreceksiniz.

11. Bu pencerede, o anda bulunduğunuz kategoriye göre (sınıf, derslik veya öğretmen) "Kaydet" tuşunu kullanarak programı bir dosya olarak kaydedebilir ya da "Çıktı" tuşunu kullanarak yazıcınızdan çıktı alabilirsiniz.



## 👨‍💻 Geliştirici
Yusuf Affan Gül

Her türlü geri bildirime ve katkıya açığım!
