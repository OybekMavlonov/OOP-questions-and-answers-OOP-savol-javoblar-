# OOP haqida savol-javoblar

### Mundarija
| No. | Savollar |
| --- | --- |
| 1 | [OOP nima?](https://github.com/OybekMavlonov/OOP-savol-javoblar#1-oop-nima) |
| 2 | [OOP ning 4 ta ustuni haqida qisqacha gapirib bering](https://github.com/OybekMavlonov/OOP-savol-javoblar#2-oop-ning-4-ustuni) |
| 3 | [Class va Obyekt orasida nima farq bor?](https://github.com/OybekMavlonov/OOP-savol-javoblar#3-class-va-obyekt-orasidagi-farq) |
| 4 | [Abstract Class va Interface orasida qanday farq bor?](https://github.com/OybekMavlonov/OOP-savol-javoblar#4-Abstract-class-va-Interface) |
| 5 | [Abstract Class oddiy Class dan nimasi bilan farq qiladi?](https://github.com/OybekMavlonov/OOP-savol-javoblar#5-Abstract-class-va-Class) |
| 6 | [Agar xossaga protected kalit so'zi qo'yilgan bo'lsa, bu nimani anglatadi?](https://github.com/OybekMavlonov/OOP-savol-javoblar#6-Protected-kalit-so'zi) |
| 7 | [AppSettingsManager class idan obyekt (instance) yaratib bo'lmaydigan qilishingiz kerak. Buni qanday qilasiz?](https://github.com/OybekMavlonov/OOP-savol-javoblar#7-Static-Class) |
| 8 | [Field va Property orasida qanday farq bor?](https://github.com/OybekMavlonov/OOP-savol-javoblar#8-Field-va-Property) |
| 9 | [Constructor qanday chaqiriladi?](https://github.com/OybekMavlonov/OOP-savol-javoblar#9-Constructor-qachon-ishga-tushadi?) |
| 10 | [Method Overloading va Overriding haqida aytib bering](https://github.com/OybekMavlonov/OOP-savol-javoblar#10-Method-overloading-va-overriding) |
| 11 | [this kalit so'zi nimani anglatadi? base kalit so'zichi?](https://github.com/OybekMavlonov/OOP-savol-javoblar#11-oop-nima) |
| 12 | [Quyidagi constructorni nimasi noto'g'ri?  public int Employee() {}](https://github.com/OybekMavlonov/OOP-savol-javoblar#12-oop-nima) |

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

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 5. Abstract class va Class
**Abstract class** - avvalgi javobga qo'shimcha tarzda, abstract classni "instantiate" qilib bo'lmaydi ya'ni abstract class asosida obyekt tuzib bo'lmaydi. 
Shuning uchun ham uni mavhum (abstract) deyiladi.

**Class** - class asosida obyekt tuzish mumkin. Abstract classda aniqlangan metod va xossalarni kerak bo'lsa "override" qilish mumkin.

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)

## 6. Protected kalit so'zi
**Protected** kalit so'zi xossa yoki metodning ko'rinish doirasini belgilaydi.

Protected qo'yilgan metod yoki xossa faqatgina shu class va avlod (child)larda ko'rinadi.

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)

## 7. Static Class
## 8. Field va Property
**Field** - classda e'lon qilingan oddiy o'zgaruvchi. Aksar holatlarda u private bo'ladi va u bilan tashqaridan faqat Property orqali ishlaymiz.

**Property** - getter va setter metodlariga ega bo'lgan maxsus o'zgaruvchi. Property ning getter va setter lari orqali classdagi field ning qiymati qaytariladi
yoki field ga qiymat beriladi.

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 9. Constructor qachon ishga tushadi?
Constructor classdagi maxsus metod bo'lib u classdan yangi instance olinayotgan vaqtda yangi obyektni tuzish vaqtida ishga tushadi.

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 10. Method overloading va overriding
**Overloading** - metodlarning nomi bir xil lekin kiruvchi/qaytaruvchi parametrlarida farqlanuvchi metodlarga qytiladi.

**Overriding** - ajdod (parent) classdagi virtual metod/xossa ni avlod (child) classda override qilish.

[Mundarijaga qaytish](https://github.com/OybekMavlonov/OOP-savol-javoblar)
## 11. 
