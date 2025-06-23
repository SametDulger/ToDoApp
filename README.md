# ToDoApp

Basit ve kullanışlı bir yapılacaklar listesi uygulaması. Vanilla JavaScript, HTML ve CSS ile geliştirilmiş, modern tarayıcılarda çalışan hafif bir web uygulamasıdır.

## Özellikler

- ✅ Yeni görev ekleme
- ✅ Görevleri tamamlandı olarak işaretleme
- ✅ Görevleri silme
- ✅ Responsive tasarım
- ✅ Zebra çizgili liste görünümü
- ✅ Hover efektleri
- ✅ Türkçe arayüz

## Kullanım

1. **Görev Ekleme**: Input alanına görev açıklamasını yazın ve "Ekle" butonuna tıklayın
2. **Görev Tamamlama**: Göreve tıklayarak tamamlandı olarak işaretleyin
3. **Görev Silme**: Görevin sağ üst köşesindeki "×" butonuna tıklayın

## Kurulum

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/SametDulger/ToDoApp.git
   cd ToDoApp
   ```

2. **Uygulamayı çalıştırın:**
   - `index.html` dosyasını herhangi bir modern web tarayıcısında açın
   - Veya yerel bir web sunucusu kullanın:
     ```bash
     # Python ile
     python -m http.server 8000
     
     # Node.js ile (http-server paketi gerekli)
     npx http-server
     ```

## Proje Yapısı

```
ToDoApp/
├── index.html      # Ana HTML dosyası
├── style.css       # Stil dosyası
├── script.js       # JavaScript işlevselliği
└── README.md       # Bu dosya
```

## Teknolojiler

- **HTML5**: Yapısal markup
- **CSS3**: Stil ve animasyonlar
- **Vanilla JavaScript**: İnteraktif işlevsellik

## Özellikler Detayı

### JavaScript İşlevleri
- `newElement()`: Yeni görev ekleme
- Görev tamamlama (click event)
- Görev silme (close button)
- Input validasyonu

### CSS Özellikleri
- Responsive tasarım
- Hover efektleri
- Zebra çizgili liste
- Smooth transitions
- Modern renk paleti

## Tarayıcı Desteği

- Chrome (önerilen)
- Firefox
- Safari
- Edge
- Modern tarayıcıların tümü
