# Merge Sort Algoritması 

Verilen dizi: **[16, 21, 11, 8, 12, 22]**

---

## 1. Adım Adım Uygulama

Merge Sort algoritması böl ve fethet (divide-and-conquer) yaklaşımını takip eder:

### Aşama 1: Bölme İşlemi
```
Orijinal: [16, 21, 11, 8, 12, 22]
         ↓
Bölme 1: [16, 21, 11] | [8, 12, 22]
         ↓
Bölme 2: [16] | [21, 11] | [8] | [12, 22]
         ↓
Bölme 3: [16] | [21] | [11] | [8] | [12] | [22]
```

### Aşama 2: Birleştirme İşlemi
```
Birleştirme 1: [16, 21] | [11] | [8, 12] | [22]
Birleştirme 2: [11, 16, 21] | [8, 12, 22]
Sonuç:       [8, 11, 12, 16, 21, 22]
```

---

## 2. Zaman Karmaşıklığı Analizi

**Big-O Gösterimi:** O(n log n)

**Açıklama:**
- Bölme aşaması: O(log n)
- Birleştirme aşaması: O(n)
- Toplam karmaşıklık: O(n log n)

---











