# 🥗 EcoGrab

> **Akıllı Gıda İsrafını Önleme ve Paylaşım Platformu**  
> Flutter ve ASP.NET Core mimarisiyle geliştirilmiş; restoranlar, marketler ve tüketiciler arasında köprü kurarak son tüketim tarihi yaklaşan gıdaların israf edilmesini önleyen, sürdürülebilir mobil gıda kurtarma platformu.

---

## 📌 Projenin Amacı ve Çözülen Problem

Her yıl tonlarca tüketilebilir gıda, tedarik zincirindeki kopukluklar ve plansız tüketim nedeniyle çöpe gitmektedir. **EcoGrab**, işletmeler ile kullanıcılar arasında gerçek zamanlı bir pazar yeri oluşturarak:
* İşletmelerin satılmayan ürünlerini indirimli paketler halinde sunmasını,
* Kullanıcıların bütçe dostu gıdaya erişmesini,
* Gıda israfının ve karbon ayak izinin azaltılmasını hedefler.

---

## 🚀 Öne Çıkan Özellikler

* 📱 **Modern & Akıcı Mobil Deneyim:** Flutter ve Dart ile geliştirilmiş kullanıcı dostu, dinamik ve duyarlı mobil arayüzler.
* 📦 **Sürpriz & İndirimli Paket Yönetimi:** İşletmelerin gün sonu stoklarını hızlıca listeleyebildiği ve kullanıcıların kolayca sipariş oluşturabildiği akışlar.
* 🔄 **Güçlü RESTful API Entegrasyonu:** ASP.NET Core ve MS SQL Server altyapısıyla desteklenen, yüksek performanslı ve güvenli veri akışı.
* 🧪 **Uçtan Uca API Testleri:** Postman koleksiyonları ile tüm endpoint'lerin doğrulanmış ve optimize edilmiş olması.

---

## 🛠️ Teknolojik Yığın

| Alan | Teknoloji | Açıklama |
| :--- | :--- | :--- |
| **Mobil Uygulama** | Flutter, Dart | Çapraz platform kullanıcı arayüzü ve durum yönetimi |
| **Backend Servisleri** | C#, ASP.NET Core | RESTful API mimarisi, kimlik doğrulama ve iş mantığı |
| **Veri Tabanı** | MS SQL Server | İlişkisel veri modelleme ve transactional sipariş yönetimi |
| **API Test & Dokümantasyon** | Postman | Servis senaryolarının kurgulanması ve otomasyon testleri |
| **Versiyon Kontrolü** | Git & GitHub | Kaynak kod yönetimi ve sürüm takibi |

---

## 🏗️ Sistem Mimarisi

```text
EcoGrab
├── 📱 Mobile (Flutter/Dart)
│   ├── lib/
│   │   ├── models/        # Veri modelleri
│   │   ├── screens/       # Kullanıcı ekranları (Arayüz)
│   │   ├── services/      # HTTP/API çağrıları
│   │   └── widgets/       # Yeniden kullanılabilir UI bileşenleri
│
└── ⚙️ Backend (ASP.NET Core / C#)
    ├── Controllers/       # REST API endpoint'leri
    ├── Services/          # İş kuralları ve validasyonlar
    ├── Data/              # DbContext ve Entity konfigürasyonları
    └── Models/            # Domain varlıkları

💻 Kurulum ve Çalıştırma
Gereksinimler
Flutter SDK (3.x veya üzeri)

.NET SDK (8.0 veya üzeri)

MS SQL Server

Android Studio / Xcode veya VS Code

1. Backend Kurulumu
Bash
git clone [https://github.com/Esma7878/EcoGrab.git](https://github.com/Esma7878/EcoGrab.git)
cd EcoGrab/backend
dotnet restore
dotnet ef database update
dotnet run
2. Mobil Uygulama Kurulumu
Bash
cd ../mobile
flutter pub get
flutter run
📄 Lisans
Bu proje MIT lisansı altında lisanslanmıştır.
