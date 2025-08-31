# TrainerAI-V1

## 🇹🇷 Türkçe

### Proje Hakkında
Bu proje, yazılım mühendisliği eğitimim sırasında geliştirdiğim bir bilgisayar görüşü uygulamasıdır. Flask web framework'ü kullanarak gerçek zamanlı bicep curl egzersizi takibi yapan bir sistem oluşturdum.

### Özellikler
- 🎯 **Gerçek Zamanlı Poz Takibi**: MediaPipe kullanarak vücut pozisyonunu algılar
- 📊 **Otomatik Tekrar Sayımı**: Bicep curl hareketlerini otomatik olarak sayar
- 📈 **İlerleme Çubuğu**: Egzersiz sırasında görsel geri bildirim sağlar
- 🏷️ **Durum Göstergesi**: "Yukarı" ve "Aşağı" pozisyonları gösterir
- 🌐 **Web Arayüzü**: Tarayıcı üzerinden kolay erişim

### Kurulum
1. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

2. Uygulamayı çalıştırın:
```bash
python app.py
```

3. Web tarayıcınızda şu adresi açın:
```
http://localhost:5001
```

### Kullanım
1. Web tarayıcınızda uygulamayı açın
2. Kamera izni verin
3. Kameranın önünde durun
4. Bicep curl egzersizi yapmaya başlayın
5. Uygulama otomatik olarak tekrarlarınızı sayacak

### Teknik Detaylar
- **Poz Algılama**: MediaPipe Pose kullanılarak 33 vücut noktası takip edilir
- **Açı Hesaplama**: Omuz, dirsek ve bilek arasındaki açı hesaplanır
- **Hareket Algılama**: 160° üzeri "Aşağı", 30° altı "Yukarı" pozisyonu olarak kabul edilir

---

## 🇺🇸 English

### About the Project
This project is a computer vision application I developed during my software engineering education. I created a system that tracks bicep curl exercises in real-time using the Flask web framework.

### Features
- 🎯 **Real-time Pose Tracking**: Detects body position using MediaPipe
- 📊 **Automatic Rep Counting**: Automatically counts bicep curl movements
- 📈 **Progress Bar**: Provides visual feedback during exercise
- 🏷️ **Status Indicator**: Shows "Up" and "Down" positions
- 🌐 **Web Interface**: Easy access through browser

### Installation
1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open this address in your web browser:
```
http://localhost:5001
```

### Usage
1. Open the application in your web browser
2. Allow camera permission
3. Stand in front of your camera
4. Start doing bicep curl exercises
5. The app will automatically count your repetitions

### Technical Details
- **Pose Detection**: Tracks 33 body points using MediaPipe Pose
- **Angle Calculation**: Calculates angle between shoulder, elbow, and wrist
- **Movement Detection**: Above 160° is "Down", below 30° is "Up" position

---

## 📁 Project Structure
```
TrainerAI-V1/
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── templates/          # HTML templates
│   ├── index.html
│   └── biceps.html
└── static/            # Static files
    └── images/
```

## 🛠️ Technologies Used
- **Backend**: Flask (Python)
- **Computer Vision**: OpenCV, MediaPipe
- **Frontend**: HTML, CSS, JavaScript
- **Mathematics**: NumPy

## 📚 Academic Context
This project was developed as part of my software engineering curriculum, demonstrating practical application of:
- Computer vision and machine learning concepts
- Web development with Flask
- Real-time data processing
- User interface design
- Software architecture principles


