# TrainerAI-V1

## 🇹🇷 Türkçe

### Proje Hakkında
Merhaba! Bu proje yazılım mühendisliği okurken yaptığım bir bilgisayar görüşü uygulaması. Flask kullanarak bicep curl egzersizlerini takip eden bir sistem yaptım. Gerçekten eğlenceli bir proje oldu! 😊

### Ne Yapıyor?
- 🎯 **Poz Takibi**: MediaPipe ile vücudunu takip ediyor
- 📊 **Tekrar Sayımı**: Bicep curl'lerini otomatik sayıyor
- 📈 **İlerleme Çubuğu**: Nasıl gittiğini gösteriyor
- 🏷️ **Durum**: "Yukarı" mı "Aşağı" mı olduğunu söylüyor
- 🌐 **Web Arayüzü**: Tarayıcıdan kolayca erişebiliyorsun

### Nasıl Kurulur?
1. Önce gerekli paketleri yükle:
```bash
pip install -r requirements.txt
```

2. Uygulamayı çalıştır:
```bash
python app.py
```

3. Tarayıcında şu adresi aç:
```
http://localhost:5001
```

### Nasıl Kullanılır?
1. Tarayıcında uygulamayı aç
2. Kameraya izin ver
3. Kameranın önünde dur
4. Bicep curl yapmaya başla
5. Uygulama tekrarlarını sayacak!

### Teknik Detaylar (Biraz Teknik 😅)
- **Poz Algılama**: MediaPipe ile 33 vücut noktasını takip ediyor
- **Açı Hesaplama**: Omuz-dirsek-bilek açısını hesaplıyor
- **Hareket Algılama**: 160° üstü "Aşağı", 30° altı "Yukarı" sayıyor

---

## 📁 Proje Yapısı
```
TrainerAI-V1/
├── app.py              # Ana uygulama
├── requirements.txt    # Gerekli paketler
├── templates/          # HTML sayfaları
│   ├── index.html
│   └── biceps.html
└── static/            # Resimler vs.
    └── images/
```

## 🛠️ Kullandığım Teknolojiler
- **Backend**: Flask (Python)
- **Bilgisayar Görüşü**: OpenCV, MediaPipe
- **Frontend**: HTML, CSS, JavaScript
- **Matematik**: NumPy

## 📚 Okul Projesi
Bu proje yazılım mühendisliği derslerimde yaptığım bir proje. Şunları öğrendim:
- Bilgisayar görüşü nasıl çalışır
- Flask ile web uygulaması yapmak
- Gerçek zamanlı veri işleme
- Kullanıcı arayüzü tasarlamak
- Yazılım mimarisi

---

## 🇺🇸 English

### About the Project
Hey! This is a computer vision app I made while studying software engineering. I built a system that tracks bicep curl exercises using Flask. It was a really fun project! 😊

### What Does It Do?
- 🎯 **Pose Tracking**: Tracks your body using MediaPipe
- 📊 **Rep Counting**: Automatically counts your bicep curls
- 📈 **Progress Bar**: Shows how you're doing
- 🏷️ **Status**: Tells you if you're "Up" or "Down"
- 🌐 **Web Interface**: Easy access through browser

### How to Install?
1. First install the required packages:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open this address in your browser:
```
http://localhost:5001
```

### How to Use?
1. Open the app in your browser
2. Allow camera permission
3. Stand in front of your camera
4. Start doing bicep curls
5. The app will count your reps!

### Technical Details (A Bit Technical 😅)
- **Pose Detection**: Tracks 33 body points using MediaPipe
- **Angle Calculation**: Calculates shoulder-elbow-wrist angle
- **Movement Detection**: Above 160° is "Down", below 30° is "Up"

---

## 📁 Project Structure
```
TrainerAI-V1/
├── app.py              # Main application
├── requirements.txt    # Required packages
├── templates/          # HTML pages
│   ├── index.html
│   └── biceps.html
└── static/            # Images etc.
    └── images/
```

## 🛠️ Technologies I Used
- **Backend**: Flask (Python)
- **Computer Vision**: OpenCV, MediaPipe
- **Frontend**: HTML, CSS, JavaScript
- **Mathematics**: NumPy

## 📚 School Project
This project was part of my software engineering coursework. I learned:
- How computer vision works
- Building web apps with Flask
- Real-time data processing
- Designing user interfaces
- Software architecture 