# ✈️ Uçak Bilet Rezervasyon Sistemi (Java Konsol Uygulaması)

Bu proje, Java dilinde nesne yönelimli programlama (OOP) prensipleri kullanılarak geliştirilmiş bir **Uçak Bilet Rezervasyon Konsol Uygulamasıdır**. Uçuşlar, uçaklar, lokasyonlar ve rezervasyon işlemleri nesnelerle modellenmiş ve kullanıcı etkileşimi konsol üzerinden sağlanmıştır.

---

## 🧩 Özellikler

- Uçak tanımları (model, marka, seri numarası, kapasite)
- Lokasyon bilgileri (ülke, şehir, havaalanı, aktif/pasif durumu)
- Uçuş oluşturma (uçak + lokasyon + saat)
- Kullanıcıdan ad, soyad ve yaş bilgisi alarak rezervasyon yapma
- Koltuk kapasitesi kontrolü: Uçakta boş koltuk yoksa rezervasyon yapılamaz
- Rezervasyon sonrası CSV dosyasına kayıt
- Her rezervasyondan sonra kullanıcıya yeniden rezervasyon yapma opsiyonu sunar
- Kalan koltuk sayısını gerçek zamanlı takip eder

---

## 🧰 Kullanılan Teknolojiler

- Java 17 veya üzeri
- Konsol tabanlı kullanıcı arayüzü
- `java.util` (List, Scanner)
- `java.io` (FileWriter, PrintWriter)

---

## 🗂️ Sınıf Yapısı

- `Ucak` : Uçak bilgilerini tutar
- `Lokasyon` : Uçuş lokasyonunu tanımlar
- `Ucus` : Uçuş bilgileri (uçak + lokasyon + saat) ve koltuk yönetimi içerir
- `Rezervasyon` : Kullanıcı rezervasyon bilgisi
- `UcakRezervasyonApp` : Ana uygulama, kullanıcı ile etkileşim ve rezervasyon akışını yönetir

---

## 🚀 Uygulamanın Çalıştırılması

1. **Java kurulu olduğundan emin olun** (`java -version` ile kontrol edebilirsiniz).
2. Kod dosyasını `UcakRezervasyonApp.java` adıyla kaydedin.
3. Konsolda aşağıdaki komutları kullanarak çalıştırın:

```bash
javac UcakRezervasyonApp.java
java UcakRezervasyonApp
