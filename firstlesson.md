### Python telimat

Salam! Sizə Python proqramlaşdırma dilini öyrətmək üçün bu README faylını təqdim edirəm. Python, sadə sintaksisa malik, güclü və çox işlənən bir proqramlaşdırma dilidir. Bu dildə öyrənərək, proqramlaşdırma sahəsində mövqe qazanacaqsınız.

### Haqqında

Python, Guido van Rossum tərəfindən yaradılmış bir proqramlaşdırma dilidir. İlk olaraq 1991-ci ildə işə salınıb, sadə və oxunaqlı sintaksisi ilə fərqlənir. Python, açıq mənbəli olaraq təqdim edilir və geniş bir istifadəçi cəmiyyətinə malikdir.

### Təlimatlar

Bu təlimatlar sizə Python proqramlaşdırma dilini öyrətmək üçün nəzərdə tutulmuşdur:

Python-a Giriş: Python syntax və məntiqini başlayın.
Dəyişənlər və Tiparlar: Dəyişənləri necə istifadə etməli və tiparlar necə işləyir?
Operatorlar: Python-da operatorların necə işlədiyini öyrənin.
İfadələr və Şərtlər: Python ifadələrini və şərtlərini başlayın.
Funksiyalar: Funksiyaların necə yazılacağını və işlədiyini öyrənin.
Modullar və Paketlər: Python modullarını və paketlərini necə istifadə etməli?

### Qoşulmaq və Yardım

Əgər Python proqramlaşdırma dili ilə bağlı suallarınız, təklifləriniz və ya problemləriniz varsa, mənə hər zaman müraciət edə bilərsiniz. Sizə yardım etməkdə məmnun olaram.

Gözəl bir Python təlimatı keçirməyə hazırsınız! Uğurlar! 🐍

# Deishenler(variables)

Əsasən, Python proqramlaşdırma dilində "dəyişənlər" kavramı çox əhəmiyyətlidir. Dəyişənlər, məlumatları saxlamaq və əməliyyatlar aparmaq üçün istifadə olunan obyektlərdir. Python'da dəyişənləri tanımlamaq və istifadə etmək çox sadədir.

Dəyişənlər adları ilə tanımlanır və dəyər atamaq üçün = operatorundan istifadə edilir. Məsələn:
Python'da fərqli növ dəyişənlər və onların tip parametrləri mövcuddur. İşte əsas dəyişən növləri:

### Integer (int)

Integer (Tam Ədəd): Bu, tam rəqəmləri ifadə etmək üçün istifadə olunur. Məsələn: 5, 10, -3.

```python
firstdigit = 5
seconddigit = 86
thirddigit = 22
```

### Float

Float (Ondaq Nöqtəli Ədəd): Bu, ondalıq nöqtəli ədədləri ifadə etmək üçün istifadə olunur. Məsələn: 3.14, 0.5, -2.75.

```python
pi = 3.14
rate = 0.05
height = 1.75
```

### String

String (Simvol Silsiləsi): Bu, mətnləri ifadə etmək üçün istifadə olunur. Məsələn: "Salam", 'Python', "123".

```python
ad = "Hikmet"
soyad = 'Savetski'
mesaj = "Yaxshi oglan ozune hec vaxt yaxshi oglan demez !!"
```

### Boolean (bool)

Boolean (Məntiqi Dəyər): Bu, True və False olmaq üzrə iki dəyərə malikdir və məntiqi əməliyyatlar üçün istifadə olunur.

```python
dogru = True
yalnis = False
```

### List

List (Siyahı): Bu, müxtəlif dəyişənlərin bir araya gəldiyi, dəyişdirilə bilən strukturdur. Məsələn: [1, 2, 3], ["Salam", "Python", "Dünya"].

```python
miqdarlar = [1, 2, 3, 4, 5]
adlar = ["Namiq", "Balaeli", "Orxan"]
```

### Tuple

Tuple (Qeyd Növü): Bu, listə oxşar bir struktur olmaqla birlikdə dəyişdirilməzdir. Məsələn: (1, 2, 3), ("Salam", "Python", "Dünya").

```python
koordinatlar = (10, 20)
renkler = ("Ag", "qara", "qirmizi")
```

### Dictionary

Dictionary (Lüğət): Bu, açar-deyər cütləri formasında məlumat saxlayan struktur olmaq üçün istifadə olunur. Məsələn: {"ad": "Məhəmməd", "yaş": 25, "dil": "Azərbaycanca"}.

```python
telefonlar = {"Məhəmməd": "+994123456789", "Aysel": "+994987654321"}
stoklar = {"kərpic": 100, "ət": 50, "un": 200}
```

### Set

Set (Dəst): Bu, təkrarlanmayan dəyərləri saxlayan bir struktur olmaq üçün istifadə olunur. Məsələn: {1, 2, 3}, {"Salam", "Python", "Dünya"}.

```python
reqemler = {1, 2, 3, 4, 5}
mevzular = {"Python", "Statistika", "Alqoritmlər"}
```

Bu dəyişən növləri proqramların müxtəlif məqsədləri üçün istifadə olunur və proqramçının məlumatı düzgün şəkildə saxlamaq və idarə etmək üçün önəmli alətlərdir.

# Elave melumat almaq isteseniz

https://www.tutorialspoint.com/python/python_variables.htm
https://www.w3schools.com/python/python_datatypes.asp

# Operatorlar

# Python proqramlaşdırma dilində əsas operator növləri

## Arifmetik Operatorlar:

Toplama (+): İki dəyişəni və ya ədədi toplamaq üçün istifadə olunur.

Çıxma (-): İki ədədi bir-birindən çıxarmaq üçün istifadə olunur.

Vurma (\*): İki ədədin hasilini tapmaq üçün istifadə olunur.

Bölünmə (/): Bir ədədi digərindən bölərkən hasilini tapmaq üçün istifadə olunur.

Üsül (\*\*): Bir ədədin digərinin üsulu olaraq qüvvətinə yüksəltmək üçün istifadə olunur.

Bölünmədən qalıq qalığı (%): İki ədədin bölünməsindən qalıq qalığını tapmaq üçün istifadə olunur.

Tam bölünmə (//): Bir ədədi digərindən bölmək və tam hissəsini tapmaq üçün istifadə olunur.

### Müqayisə Operatorları:

Böyük (>): İki ədədi müqayisə edərək, böyük olduğunu yoxlamaq üçün istifadə olunur.

Kiçik (<): İki ədədi müqayisə edərək, kiçik olduğunu yoxlamaq üçün istifadə olunur.

Böyük bərabərdir (>=): İki ədədi müqayisə edərək, böyük bərabərdir və ya kiçik bərabər olduğunu yoxlamaq üçün istifadə olunur.

Kiçik bərabərdir (<=): İki ədədi müqayisə edərək, kiçik bərabərdir və ya kiçik bərabər olduğunu yoxlamaq üçün istifadə olunur.

Bərabərdir (==): İki ədədin bərabər olduğunu yoxlamaq üçün istifadə olunur.

Bərabər deyil (!=): İki ədədin bərabər olmadığını yoxlamaq üçün istifadə olunur.

### Məntiqi Operatorlar:

Və (and): Hər iki ifadə də doğru olduğu təqdirdə, vərəqədəki ifadə doğru olur.

Və ya (or): İki ifadənin hər hansı biri doğru olduğu təqdirdə, vərəqədəki ifadə doğru olur.

Deyil (not): İfadənin əksini göstərir. Məsələn, doğru ifadəni yalnışa, yalnış ifadəni doğruya çevirir.

### Menimseme Operatorları:

Eşitlik (=): Bir dəyişənə dəyər mənimsətmək üçün istifadə olunur.

Artırma (+=): Bir dəyişənin dəyərini artırmaq üçün istifadə olunur.

Azaltma (-=): Bir dəyişənin dəyərini azaltmaq üçün istifadə olunur.

Vurma (\*=): Bir dəyişənin dəyərini vurmaq üçün istifadə olunur.

Bölünmə (/=): Bir dəyişənin dəyərini bölmək üçün istifadə olunur.

# If , else , elif

Əgər Python proqramlaşdırma dilində şərtləri öyrənmək istəyirsinizsə, "if", "else" və "elif" ifadələri ən əhəmiyyətli strukturlardandır. Bu ifadələr, proqramınızın müxtəlif şərtlərə uyğun davranışını təyin etmək üçün istifadə olunur.

if: "if" ifadəsi, təyin edilmiş bir şərtin doğru olduğunu yoxlayır. Əgər şərt doğru olduqda, ifadə daxilindəki blok işlədirilir. Əgər şərt yanlışdırsa, ifadə bloku atlanır.

```python

a = 5
if a > 3:
    print("a 3-dən böyükdür")
Bu nümunədə, əgər "a" dəyişəni 3-dən böyükdürsə, "a 3-dən böyükdür" ifadəsi çap olunur.
```

else: "else" ifadəsi, əgər əvvəlki "if" şərti doğru deyilsə, yəni əgər əvvəlki "if" şərtindən sonra heç bir şərt doğru deyilsə, bu blok işlədirilir.

```python
a = 2
if a > 3:
    print("a 3-dən böyükdür")
else:
    print("a 3-dən kiçikdir və ya bərabərdir")
Bu nümunədə, əgər "a" dəyişəni 3-dən böyük deyilsə, "a 3-dən kiçikdir və ya bərabərdir" ifadəsi çap olunur.
```

elif: "elif" ifadəsi, əgər əvvəlki "if" şərti yanlışdırsa, yeni bir şərt yoxlayır. Əgər bu əvvəlki "if" və "elif" şərtlərindən heç biri doğru deyilsə, "else" bloku işlədirilir.

```python

a = 2
if a > 3:
    print("a 3-dən böyükdür")
elif a == 3:
    print("a 3-ə bərabərdir")
else:
    print("a 3-dən kiçikdir")
```

Bu nümunədə, əgər "a" dəyişəni 3-dən böyük deyilsə və "a" 3-ə bərabər deyilsə, "a 3-dən kiçikdir" ifadəsi çap olunur.

# Let's go practice

İstifadəçidən iki ədəd daxil etməsini tələb edin.
İstifadəçidən hansı arifmetik əməliyyatı (toplama, çıxma, vurma, bölünmə) etmək istədiyini soruşun.
Daxil edilmiş ədədlərə və seçilmiş arifmetik əməliyyatına görə uyğun nəticəni hesablayın.
Nəticəni istifadəçiyə çap edin.
Bu təlimatlar əsasında, tələb olunan funksionalı implement edərək, istifadəçinin daxil etdiyi ədədlərin və seçilmiş əməliyyatın nəticəsini dərhal göstərən bir Python skripti yazmalıdırlar.

Bu təlimatlar, ən əsas operatorlar və şərtlər mövzusunda prakitik bir tətbiqat təmin edəcəkdir. İstifadəçilər proqramlarını yazarkən müxtəlif şərt strukturlarını və arifmetik əməliyyatları istifadə etməyi öyrənəcəklər.
