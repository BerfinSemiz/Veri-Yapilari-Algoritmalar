# Insertion Sort Algoritması 

**İncelenecek dizi:** [22, 27, 16, 2, 18, 6]

---

## 1. Algoritma Adımları

Insertion Sort, her elemanı doğru konumuna yerleştirerek sıralama yapar:

### Adım 1: İlk eleman (22) zaten doğru yerde
```
[22, 27, 16, 2, 18, 6]
```

### Adım 2: 27'yi kontrol et (22'den büyük, yerinde kalır)
```
[22, 27, 16, 2, 18, 6]
```

### Adım 3: 16'yı yerleştir (22 ve 27'den küçük, başa gelir)
```
[16, 22, 27, 2, 18, 6]
```

### Adım 4: 2'yi yerleştir (en küçük, en başa)
```
[2, 16, 22, 27, 18, 6]
```

### Adım 5: 18'i yerleştir
```
[2, 16, 18, 22, 27, 6]
```

### Adım 6: 6'yı yerleştir
```
[2, 6, 16, 18, 22, 27]
```

---

## 2. Zaman Karmaşıklığı

**Big-O Notasyonu:** O(n²)

**Açıklama:**
- En kötü durum: O(n²) - ters sıralı dizi
- En iyi durum: O(n) - zaten sıralı dizi
- Ortalama durum: O(n²)

---

## 3. Case Analizi

**Zaman Karmaşıklığı Türleri:**
- **Best Case:** Aranan eleman dizinin başında
- **Average Case:** Aranan eleman ortada
- **Worst Case:** Aranan eleman sonda

### 18 Sayısının Analizi
Sıralama sonrası 18 sayısı **Average Case** kapsamına girer çünkü dizinin ortasında yer alır.

---

## 4. Ek Örnek

**Dizi:** [7, 3, 5, 8, 2, 9, 4, 15, 6]

### İlk 4 Adım:

**Adım 1:** [2, 7, 3, 5, 8, 9, 4, 15, 6]
**Adım 2:** [2, 3, 7, 5, 8, 9, 4, 15, 6]
**Adım 3:** [2, 3, 4, 7, 5, 8, 9, 15, 6]
**Adım 4:** [2, 3, 4, 5, 7, 8, 9, 15, 6]

---


