# Satrlarni kesish (slicing)

## Slicing01

`s` satri berilgan. Satrning boshidan to'rtta belgini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "Alla"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "Tosh"
```

---

## Slicing02

`s` satri berilgan. Satrning oxiridan to'rtta belgini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "urod"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "kent"
```

---

## Slicing03

`s` satri berilgan. Birinchi va oxirgi belgidan tashqari barcha belgilarni qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "llamuro"
```

**Misol 2:**

```Python
Kirish: s="Xakimov"
Chiqarish: "akimo"
```

---

## Slicing04

`s` satri va `n` soni berilgan. Satrning boshidan `n` ta belgini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod", n=3
Chiqarish: "All"
```

**Misol 2:**

```Python
Kirish: s="Xakimov", n=5
Chiqarish: "Xakim"
```

---

## Slicing05

`s` satri va `n` soni berilgan. Satrning oxiridan `n` ta belgini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod", n=3
Chiqarish: "rod"
```

**Misol 2:**

```Python
Kirish: s="Xakimov", n=2
Chiqarish: "ov"
```

---

## Slicing06

`s` satri va `n` soni berilgan. Satr boshidan `n` ta belgini olib tashlab, qolgan qismini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod", n=4
Chiqarish: "murod"
```

**Misol 2:**

```Python
Kirish: s="Toshkent", n=4
Chiqarish: "kent"
```

---

## Slicing07

`s` satri va `n` soni berilgan. Satr oxiridan `n` ta belgini olib tashlab, qolgan qismini qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod", n=5
Chiqarish: "Alla"
```

**Misol 2:**

```Python
Kirish: s="Xakimov", n=2
Chiqarish: "Xakim"
```

---

## Slicing08

`s` satri berilgan. Toq o'rinlardagi (1-, 3-, 5-, ...) belgilarni qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "Almrd"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "Tskn"
```

---

## Slicing09

`s` satri berilgan. Juft o'rinlardagi (2-, 4-, 6-, ...) belgilarni qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "lauo"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "ohet"
```

---

## Slicing10

`s` satri, `n` va `k` sonlari berilgan. `n` dan `k` gacha (k kirmaydi) bo'lgan indekslardagi belgilarni qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod Xakimov", n=10, k=17
Chiqarish: "Xakimov"
```

**Misol 2:**

```Python
Kirish: s="Allamurod", n=2, k=5
Chiqarish: "lam"
```

---

## Slicing11

`s` satri berilgan. Satrni teskari tartibda qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "dorumallA"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "tnekhsoT"
```

---

## Slicing12

So'z berilgan. Agar u palindrom bo'lsa (teskarisi o'ziga teng) `True`, aks holda `False` qaytaring. Kesishdan foydalaning.

**Misol 1:**

```Python
Kirish: s="kiyik"
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: s="Allamurod"
Chiqarish: False
```

---

## Slicing13

Allamurodning tug'ilgan sanasi "KK.OO.YYYY" ko'rinishida berilgan. Uni "YYYY-OO-KK" ko'rinishiga keltirib qaytaring.

**Misol 1:**

```Python
Kirish: sana="15.03.2000"
Chiqarish: "2000-03-15"
```

**Misol 2:**

```Python
Kirish: sana="01.09.2026"
Chiqarish: "2026-09-01"
```

---

## Slicing14

Allamurodning 16 xonali karta raqami berilgan. Dastlabki 4 ta va oxirgi 4 ta raqamni qoldirib, "XXXX **** **** YYYY" ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: karta="8600123456781234"
Chiqarish: "8600 **** **** 1234"
```

---

## Slicing15

Allamurodning telefon raqami "+998XXYYYZZWW" ko'rinishida bo'sh joysiz berilgan. Uni "+998 XX YYY ZZ WW" ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: telefon="+998901234567"
Chiqarish: "+998 90 123 45 67"
```

---

## Slicing16

Ism va familiya berilgan. "Familiya I." ko'rinishidagi qisqa yozuvni qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: "Xakimov A."
```

---

## Slicing17

Uzunligi juft bo'lgan so'z berilgan. Uning ikki yarmini o'rnini almashtirib qaytaring. `len()` va kesishdan foydalaning.

**Misol 1:**

```Python
Kirish: s="Toshkent"
Chiqarish: "kentTosh"
```

**Misol 2:**

```Python
Kirish: s="Python"
Chiqarish: "honPyt"
```

---

## Slicing18

Allamurod rezyume faylining nomini o'zgartirmoqda. ".pdf" bilan tugaydigan fayl nomi berilgan. Kengaytmani ".docx" ga almashtirib qaytaring.

**Misol 1:**

```Python
Kirish: fayl="allamurod_cv.pdf"
Chiqarish: "allamurod_cv.docx"
```

---

## Slicing19

Allamurodning kod yozish vaqti "SS:DD:SS" ko'rinishida berilgan. Uni soniyalarga aylantirib qaytaring.

**Misol 1:**

```Python
Kirish: vaqt="05:33:20"
Chiqarish: 20000
```

**Misol 2:**

```Python
Kirish: vaqt="01:01:01"
Chiqarish: 3661
```

---

## Slicing20

Ism, familiya va tug'ilgan yil berilgan. Login yarating: familiyaning dastlabki 3 harfi + ismning birinchi harfi + yilning oxirgi 2 raqami.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov", yil=2000
Chiqarish: "XakA00"
```

**Misol 2:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov", yil=1998
Chiqarish: "XakA98"
```

