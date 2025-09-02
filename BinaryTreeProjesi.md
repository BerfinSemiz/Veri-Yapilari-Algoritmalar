# İkili Arama Ağacı Oluşturma Rehberi

Merhaba arkadaşlar! Bugün birlikte İkili Arama Ağacı (Binary Search Tree) oluşturmayı öğreneceğiz! 🌳

## Görevimiz
Şu diziyi kullanacağız: **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

Amacımız: Her elemanın nereye yerleşeceğini göstererek bir BST oluşturmak!

---

## Adım Adım İnşa Edelim! 🚀

### 1. Adım: Kök ile başlayalım
```
    7
```

### 2. Adım: 5'i ekleyelim (7'den küçük, sola gider)
```
    7
   /
  5
```

### 3. Adım: 1'i ekleyelim (7 ve 5'ten küçük, 5'in soluna gider)
```
    7
   /
  5
 /
1
```

### 4. Adım: 8'i ekleyelim (7'den büyük, sağa gider)
```
    7
   / \
  5   8
 /
1
```

### 5. Adım: Devam edelim...
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

---

## Sonuç Ağaç Yapısı

İşte tamamlanmış İkili Arama Ağacımız:

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

**Nasıl çalışır:**
- **Kök:** 7 (başlangıç noktamız)
- **Sol alt ağaç:** 7'den küçük tüm sayılar
- **Sağ alt ağaç:** 7'den büyük tüm sayılar
- Her düğüm BST özelliğini takip eder: sol çocuk < ebeveyn < sağ çocuk

Harika değil mi? 😊


