# OOP haqida savol-javoblar

### Mundarija
| No. | Savollar |
| --- | --- |
| 1 | [OOP nima?](https://github.com/OybekMavlonov/OOP-savol-javoblar#1-oop-nima) |
| 2 | [OOP ning 4 ta ustuni haqida qisqacha gapirib bering](https://github.com/OybekMavlonov/OOP-savol-javoblar#2-oop-ning-4-ustuni) |
| 3 | [Class va Obyekt orasida nima farq bor?](https://github.com/OybekMavlonov/OOP-savol-javoblar#3-class-va-obyekt-orasidagi-farq) |
| 4 | [Abstract Class va Interface orasida qanday farq bor?] |
| 5 | [Abstract Class oddiy Class an nimasi bilan farq qiladi?] |
| 6 | [O'zgaruvchini biron turga/class ga tegishli ekanligini qanday qilib tekshirasiz?] |
| 7 | [Ajdod (Parent) class idagi metodni avlod (child) class ida boshqacha ishlashi uchun nima qilish kerak?] |
| 8 | [Agar xossaga protected kalit so'zi qo'yilgan bo'lsa, bu nimani anglatadi?] |
| 9 | [AppSettingsManager class idan obyekt (instance) yaratib bo'lmaydigan qilishingiz kerak. Buni qanday qilasiz?] |
| 10 | [Field va Property orasida qanday farq bor?] |
| 11 | [Constructor qanday chaqiriladi?] |
| 12 | [Method Overloading va Overriding haqida aytib bering] |
| 13 | [this kalit so'zi nimani anglatadi? base kalit so'zichi?] |
| 14 | [Quyidagi constructorni nimasi noto'g'ri?  public int Employee() {}] |

## 1. OOP nima?
OOP yoki Object Oriented Programming bu obyekt asosida qurilgan dasturlash usuli. OOP ga ko'ra, dasturda ishlatilgan ma'lumotlar interfeys va classlar orqali
ifodalanadi hamda "obyekt" ko'rinishida ishlatiladi. "Obyekt" dagi ma'lumot holati maydon (field) yoki xossa (property) ko'rinishida saqlanadi. "Obyekt" lar bilan ishlash undagi "method" lar orqali bajariladi.
[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 2. OOP ning 4 ustuni
### 1) Abstraction
Murakkablikni berkitih maqsadida keraksiz tafsilotlarni foydalanuvchidan yashirish (**abstract class/interface**)
### 2) Inheritance
Avlod (Child) obyektlarni ajdod (parent) obyektlarning xususiyatlaridan meros olishi (**base/super class derived/sub class**)
### 3) Polymorphism
Obyektning turiga qarab u bilan o'ziga xos ravishda ishlash qobiliyati. Masalan, shakl abstrakt klassining Draw() metodi doira va uchburchak uchun o'ziga xos tarzda 
ishlaydi (**virtual/override**) 
### 4) Encapsulation
Klassdagi o'zgaruvchi va ichki metodlarni tashqaridan chaqirib bo'lmaydigan qilish (**getter/setter**)
[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 3. Class va Obyekt orasidagi farq
**Class** - qolip, ya'ni unda obyektning qanday xossa va metodlarga ega bo'lishi yozilgan bo'ladi
class Car {}

**Obyekt** - class asosida tuzilgan aniq obyekt
let audi = new Car()

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 4. Abstract class va Interface
**Abstract class** - avlod (child) classlar meros oladigan hamda xohlasa o'zgartirishi mumkin bo'lgan xossa va metodlarni o'zida jamlaydi. Unda metod va xossalarni
"implementatsiyasi" ham bo'lishi mumkin.

**Interface** - class tomonidan qo'llanilishi mumkin bo'lgan metod va xossalarni ta'riflaydi xolos. Interfeysda metod va xossalarni implementatsiyasi bo'lmaydi.
