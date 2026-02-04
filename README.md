# Green Wave Calculator / Yeşil Dalga Optimizasyon Yazılımı

[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
[![Tech](https://img.shields.io/badge/tech-C%23%20%7C%20.NET-purple.svg)](https://dotnet.microsoft.com/)
[![Type](https://img.shields.io/badge/type-Showcase-blue.svg)](#)

[EN - English](#english) | [TR - Türkçe](#türkçe)

---

<a name="english"></a>
## 🇬🇧 English (EN)

### 📢 About This Repository
**Note:** This repository is for **demonstration purposes only**. It showcases the technical capabilities, UI design, and engineering logic of the software. The source code or the executable file is not publicly available here.

### Description
**Green Wave Calculator** is a professional desktop application developed to solve complex traffic engineering problems. It is built using **C#** and the **.NET** framework. The main goal of the software is to optimize the timing of traffic lights at sequential intersections, commonly known as Signal Coordination.

In traffic engineering, a "Green Wave" allows vehicles to pass through multiple intersections without stopping. This software calculates the necessary time differences (offsets) between traffic lights to create this continuous flow. It visualizes the data on a custom-drawn **Time-Space Diagram**.

### 🛠 Technical & Engineering Background
This project combines software development skills with Intelligent Transportation Systems (ITS) principles:

*   **Technology Stack:** The application is built with **C#** on the **.NET** platform. It uses Object-Oriented Programming (OOP) to manage complex data structures like Intersections, Phases, and Signal Groups.
*   **Custom Visualization:** The Time-Space Diagram is not a standard chart component. It is a custom graphical implementation (GDI+) that draws dynamic traffic flows based on distance and time variables.
*   **Optimization Algorithms:** The software runs algorithms to find the "Best Fit." It compares the "One-Way" speed priority against a "Two-Way" balanced flow to suggest the most efficient signal plan.

### 📺 Demo Video
You can watch the interface, data input process, and the optimization graph in action below:

https://github.com/user-attachments/assets/cc8a487c-af3d-4e0a-9e4e-daaca8b6125e

### Key Features
*   **Sequential Intersection Logic:** Users can define the distance (meters) and average speed (km/h) between multiple intersections.
*   **Signal Phasing System:** Detailed control over signal phases. You can set Green time, Yellow time, and Red Clearance intervals for safety.
*   **Time-Space Diagram:** A real-time graph that shows the "Green Band." It helps engineers see where the traffic flow is blocked and where it is open.
*   **Offset Calculation:** Automatically calculates the start time for each traffic light to synchronize the system.
*   **Intelligent Suggestions:** The system analyzes the "Wait Time" for both directions. If the delay is too high, it suggests changing the phase order or adjusting the cycle length.

### 🔍 Keywords
`Traffic Engineering`, `Green Wave Optimization`, `Signal Timing`, `C# .NET Application`, `Time-Space Diagram`, `Intelligent Transportation Systems (ITS)`, `Traffic Simulation`, `Offset Calculation`.

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe (TR)

### 📢 Bu Repo Hakkında
**Not:** Bu depo sadece **tanıtım amaçlıdır**. Yazılımın teknik yeteneklerini, arayüz tasarımını ve mühendislik mantığını sergiler. Kaynak kodlar veya çalıştırılabilir uygulama dosyası (exe) bu depoda halka açık değildir.

### Proje Tanımı
**Yeşil Dalga Optimizasyon Yazılımı**, karmaşık trafik mühendisliği problemlerini çözmek için geliştirilmiş profesyonel bir masaüstü uygulamasıdır. **C#** ve **.NET** teknolojileri kullanılarak inşa edilmiştir. Yazılımın temel amacı, sıralı kavşaklardaki trafik ışıklarının zamanlamasını (Sinyal Koordinasyonu) optimize etmektir.

Trafik mühendisliğinde "Yeşil Dalga", araçların birden fazla kavşaktan durmadan geçebilmesini sağlar. Bu yazılım, bu kesintisiz akışı oluşturmak için trafik ışıkları arasındaki gerekli zaman farklarını (ofsetleri) hesaplar. Verileri özel olarak çizilmiş bir **Zaman-Mesafe Diyagramı** üzerinde görselleştirir.

### 🛠 Teknik ve Mühendislik Altyapısı
Bu proje, yazılım geliştirme becerilerini Akıllı Ulaşım Sistemleri (AUS) prensipleriyle birleştirir:

*   **Teknoloji Yığını:** Uygulama **.NET** platformu üzerinde **C#** ile geliştirilmiştir. Kavşaklar, Fazlar ve Sinyal Grupları gibi karmaşık veri yapılarını yönetmek için Nesne Yönelimli Programlama (OOP) kullanır.
*   **Özel Görselleştirme:** Kullanılan Zaman-Mesafe Diyagramı standart bir grafik bileşeni değildir. Mesafe ve zaman değişkenlerine dayalı olarak dinamik trafik akışlarını çizen özel bir grafik uygulamasıdır (GDI+).
*   **Optimizasyon Algoritmaları:** Yazılım, "En İyi Uyum"u bulmak için algoritmalar çalıştırır. En verimli sinyal planını önermek için "Tek Yönlü" hız önceliği ile "Çift Yönlü" dengeli akışı karşılaştırır.

### 📺 Tanıtım Videosu
Arayüzü, veri giriş sürecini ve optimizasyon grafiğinin çalışmasını aşağıdaki videodan izleyebilirsiniz:

https://github.com/user-attachments/assets/cc8a487c-af3d-4e0a-9e4e-daaca8b6125e

### Temel Özellikler
*   **Sıralı Kavşak Mantığı:** Kullanıcılar, çoklu kavşaklar arasındaki mesafeyi (metre) ve ortalama hızı (km/s) tanımlayabilir.
*   **Sinyal Faz Sistemi:** Sinyal fazları üzerinde detaylı kontrol sağlar. Güvenlik için Yeşil süre, Sarı süre ve Kırmızı Boşluk (Red Clearance) aralıklarını ayarlayabilirsiniz.
*   **Zaman-Mesafe Diyagramı:** "Yeşil Bant" aralığını gösteren gerçek zamanlı bir grafik. Mühendislerin trafik akışının nerede tıkandığını ve nerede açık olduğunu görmesine yardımcı olur.
*   **Ofset Hesaplama:** Sistemi senkronize etmek için her bir trafik ışığının başlangıç zamanını otomatik olarak hesaplar.
*   **Akıllı Öneriler:** Sistem, her iki yön için "Bekleme Süresi"ni analiz eder. Eğer gecikme çok yüksekse, faz sırasını değiştirmeyi veya devre süresini (cycle length) ayarlamayı önerir.

### 🔍 Anahtar Kelimeler
`Trafik Mühendisliği`, `Yeşil Dalga Optimizasyonu`, `Sinyal Zamanlama`, `C# .NET Uygulama`, `Zaman-Mesafe Diyagramı`, `Akıllı Ulaşım Sistemleri (AUS)`, `Trafik Simülasyonu`, `Ofset Hesaplama`.

---

### 📧 Contact / İletişim
Created by **Mete Sepetcioğlu**.
For inquiries or feedback, please contact via GitHub profile.
Sorularınız veya geri bildirimleriniz için GitHub profili üzerinden iletişime geçebilirsiniz.
