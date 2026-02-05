# n8n Sponsor Outreach Automation

Teknofest ve proje süreçlerinde sponsorluk maillerini tek tek atmak yerine, süreci otomatize etmek için geliştirdiğim n8n workflow projesi.

Sistem, yerel dosyalarla uğraşmak yerine veriyi direkt **Google Drive** üzerindeki Excel dosyasından çeker ve **Gmail** üzerinden kişiselleştirilmiş (İsim/Kurum bazlı) gönderim yapar.

### Özellikler
* **Cloud-Based Veri Yönetimi:** Excel listesi Google Drive'da tutulduğu için, workflow'u durdurmadan listeyi güncellemek mümkündür.
* **XLSX Parsing:** Excel verisini okuyup JSON formatına çevirerek işler.
* **Kişiselleştirme:** Her satır için dinamik içerik oluşturur.

### Kullanılan Teknolojiler
* n8n (Workflow Automation)
* Google Drive API
* Gmail / SMTP

### Yapılacaklar (To-Do)
- [ ] Maillere otomatik PDF (Sponsorluk dosyası) ekleme özelliği.
- [ ] Gönderim sonrası log tutma sistemi.

### Not
Repo içerisinde workflow'un mantıksal şeması (.json) bulunmaktadır. Kişisel API anahtarları güvenlik nedeniyle dahil edilmemiştir.
