
### 🧾 **README

````markdown
# Image Color Filtering Basics with OpenCV

This notebook demonstrates fundamental **digital image processing** techniques using **Python, OpenCV, NumPy**, and **Matplotlib**.

## 📚 Topics Covered
- Reading and displaying images with OpenCV (`cv2.imread`, `cv2.cvtColor`, `plt.imshow`)
- Understanding RGB color channels
- Pixel-wise manipulation using NumPy
- Color-based segmentation and masking
- Recoloring selected parts of an image
- Examples:
  - Selecting dark (black) pixels and recoloring them (e.g., hair)
  - Converting all non-white pixels to turquoise
  - Changing red-colored regions (e.g., a jersey) to blue

## 🧠 Concepts Learned
- How to access and modify pixel values
- Logical operations on image arrays
- How color thresholds can isolate regions in an image
- Visualization of before-and-after effects using `matplotlib`

## 🛠️ Requirements
```bash
pip install opencv-python matplotlib numpy
````

## ▶️ How to Run

1. Download this notebook and the required image (e.g., `bonus.jpg`).
2. Run each cell sequentially in Jupyter Notebook or Google Colab.
3. Observe the changes in image coloration and segmentation results.

## 🖼️ Example Output

* Black hair recolored to turquoise
* Entire body recolored while preserving white background
* Red jersey changed to blue

---

**Author:** Berkan Suçsuz
**Course:** Fundamentals of Digital Image Processing (Week 6)

````

---

### 🧾 **README (Türkçe sürüm)**
```markdown
# OpenCV ile Görüntüde Renk Filtreleme Temelleri

Bu Jupyter Notebook, **OpenCV** ve **NumPy** kullanarak dijital görüntü işleme temellerini uygulamalı olarak anlatmaktadır.

## 🎯 İşlenen Konular
- OpenCV ile görüntü okuma ve görüntüleme (`cv2.imread`, `cv2.cvtColor`, `plt.imshow`)
- RGB renk kanallarının anlaşılması
- Piksel bazlı işlemler (NumPy ile)
- Renk tabanlı maskeleme ve bölütleme (color segmentation)
- Seçilen bölgelerin yeniden renklendirilmesi
- Uygulama örnekleri:
  - Siyah (koyu) piksellerin tespiti ve turkuaz renge dönüştürülmesi (ör. saç bölgesi)
  - Beyaz arka plan hariç tüm bölgelerin renklendirilmesi
  - Kırmızı formanın maviye dönüştürülmesi

## 🧠 Kazanımlar
- Piksel erişimi ve düzenleme mantığı
- Renk eşiği (threshold) kullanarak görüntü bölütleme
- `matplotlib` ile görselleştirme teknikleri

## 🔧 Gereksinimler
```bash
pip install opencv-python matplotlib numpy
````

## ▶️ Nasıl Çalıştırılır

1. Bu dosyayı ve ilgili resmi (ör. `bonus.jpg`) indirin.
2. Jupyter Notebook veya Google Colab ortamında hücreleri sırayla çalıştırın.
3. Görüntüdeki renk değişimlerini inceleyin.

## 📷 Örnek Sonuçlar

* Siyah saçlar → Turkuaz
* Tüm vücut → Turkuaz (beyaz zemin korunur)
* Kırmızı forma → Mavi

