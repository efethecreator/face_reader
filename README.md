#  Face Reader - Gerçek Zamanlı Duygu Tanıma

Bu proje, bilgisayar kamerası aracılığıyla bir kişinin yüz ifadelerini analiz eder ve duygu durumunu gerçek zamanlı olarak bir emoji ile birlikte gösterir.

---

##  Özellikler

- Gerçek zamanlı yüz algılama
- Duygu tanıma (mutlu, üzgün, kızgın vb.)
- "Yüz algılanamadı" uyarısı
- 'q' tuşu ile kolay çıkış

---

##  Kullanılan Teknolojiler

- [OpenCV](https://opencv.org/)
- [DeepFace](https://github.com/serengil/deepface)
- Python

---

##  Kurulum

Proje dosyasını klonlayın:

```bash
git clone https://github.com/efethecreator/face-reader.git
cd face-reader


python -m venv venv
venv\Scripts\activate     # Windows için
source venv/bin/activate  # macOS/Linux için

pip install opencv-python deepface

python face_reader.py


