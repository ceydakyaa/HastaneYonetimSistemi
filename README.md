 Hastane Yönetim Sistemi

Bu proje, bir hastane yönetim sistemidir. Hasta giriş, doktor giriş, randevu alma ve branş yönetimi gibi temel işlevleri içermektedir. Proje **C#**, **Windows Forms (WinForms)** ve **Microsoft SQL Server** kullanılarak geliştirilmiş olup, **ADO.NET** ile veritabanı işlemleri gerçekleştirilmiştir.

 Proje Özellikleri

1. Hasta Modülü
- Hastalar sisteme kayıt olabilir.
- Hasta girişi yapılabilir.
- Randevu alma işlemi gerçekleştirilebilir.

2. Doktor Modülü
- Doktorlar giriş yapabilir.
- Kendilerine atanmış randevuları görüntüleyebilir.
- Hasta bilgilerine erişebilir.

3. Yönetici (Sekreter) Modülü
- Branş ekleme, güncelleme ve silme işlemleri yapılabilir.
- Doktor atama ve yönetimi sağlanabilir.
- Hastaların randevularını düzenleyebilir.
- Duyuru ekleme işlemi yapılabilir.

4. Randevu Yönetimi
- Hastalar uygun branş ve doktora randevu alabilir.
- Randevu saatleri sistem tarafından kontrol edilir.
- Doktorlar kendi randevularını görüntüleyebilir.

5. Veritabanı İşlemleri (CRUD)
Projede ADO.NET kullanılarak aşağıdaki CRUD işlemleri yapılmaktadır:
- **Create:** Yeni hasta, doktor, randevu ve branş ekleme.
- **Read:** Hastalar, doktorlar, randevular ve branşların listelenmesi.
- **Update:** Hastalar, doktorlar ve randevuların güncellenmesi.
- **Delete:** İlgili kayıtların silinmesi.

 Kullanılan Teknolojiler
- **C# (.NET Framework)**
- **Windows Forms (WinForms)**
- **Microsoft SQL Server**
- **ADO.NET**
- **SQL (T-SQL)**

 Kurulum ve Kullanım

1. Veritabanı Kurulumu
1. Microsoft SQL Server'ı yükleyin ve bir veritabanı oluşturun.
2. `Tbl_Hastalar`, `Tbl_Doktorlar`, `Tbl_Branslar`, `Tbl_Randevular` gibi tabloları oluşturun.
3. **Bağlantı dizesini (Connection String) güncelleyin:**
   - `BaglantiSinifi.cs` içinde yer alan `sqlbaglantisi()` metodundaki **SQL Server bağlantı dizesini** kendi veritabanınıza uygun şekilde düzenleyin.

2. Projeyi Çalıştırma
1. **Visual Studio** ile projeyi açın.
2. `Proje_Hastane.sln` dosyasını çalıştırın.
3. Giriş ekranından hasta, doktor veya sekreter olarak giriş yapabilirsiniz.

Ekran Görüntüleri

Hasta Giriş Ekranı

![Image](https://github.com/user-attachments/assets/eb09000c-523a-4db0-8910-1495dcfaa73c)
  
 Doktor Paneli

![Image](https://github.com/user-attachments/assets/a7b99555-7b21-4279-ab91-8b949599b75b)
  
- Randevu Yönetim Paneli
- Branş Yönetim Paneli
---
Bu proje, temel hastane yönetim işlevlerini kapsayan bir **Masaüstü Uygulaması** olup, küçük ve orta ölçekli hastaneler için bir yönetim çözümü sunmayı amaçlamaktadır.

