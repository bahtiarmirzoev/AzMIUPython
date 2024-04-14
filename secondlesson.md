# List , Set , Dictionary , Tuple
# List (Siyahı):
Siyahılar dəyişdirilə bilən və sıralanmış məlumat elementlərini saxlayır.

Siyahı elementləri hər hansı bir məlumat növü (məsələn, rəqəm, mətn, siyahı və s.) ola bilər.

Siyahılar len() funksiyası ilə uzunluğu hesablanar və indexlənir (0-dan başlayaraq).

Məsələn, ["Ali", 25, "Bakı", True] kimi bir siyahıda fərqli növ məlumatlar olabilir.
``` python 
meyvelər = ["Alma", "Armud", "Nar", "Üzüm", "Limons"]
raqamlar = [1, 2, 3, 4, 5]
kəslər = [3.14, 2.718, 1.618]
```

# Set
Set (Düzgün cədvəl):

Düzgün cədvəllər unikal (təkrarlanmayan) elementləri saxlayır.

Setlərə elementlər əlavə olunur, amma həmin elementlər təkrarlanan daxili olaraq qəbul olunmur.

Setlər, matematikada olduğu kimi cədvəllər arasında əməlliyyatlar aparmaq üçün işə yarayır.

Məsələn, {1, 2, 3, 4, 5} kimi bir set 5 fərqli rəqəmi saxlayır.
``` python
meyvelər = {"Alma", "Armud", "Nar", "Üzüm", "Limons"}
print(meyvelər)
```
# Dictionary
Lüğətlər açar-verilən cütlüklərinə əsaslanan məlumat elementlərini saxlayır.

Hər bir açar, ona məxsus bir məlumat elementinə əlavə olunur.

Açarlar tipik olaraq mətn və ya rəqəm olur və dəyişdirilə bilməz.

Lüğətlər daxili elementlərə key: value formatında müraciət edilərək istifadə olunur.

Məsələn, { 'ad': 'Ali', 'yaş': 25, 'şəhər': 'Bakı'} kimi bir lüğətdə, "ad", "yaş" və "şəhər" kimi açarlarla məlumat əlaqələndirilir.

``` python
telebe = {
    "ad": "Nigar",
    "yaş": 20,
    "fənlər": ["Kimya", "Biologiya"],
    "şəhər": "Bakı"
}

print(telebe)
```
# Tuple 
Tuple'lar dəyişdirilə bilməyən, qəti və sıralı məlumat elementlərini saxlayır.

Bir dəyişəni və ya məlumat qrupunu saxlamaq üçün istifadə olunur.

Tuple'lar parantez ( ) ilə təyin olunur.

Məsələn, (1, 2, 3, 4, 5) kimi bir tuple 5 ədəd məlumat elementini saxlayır və dəyişdirilə bilməz.

``` python 
meyvelər = ("Alma", "Armud", "Nar", "Üzüm", "Limons")
print(meyvelər)
```
 # List methodlari
 
Əminəm ki, sizə Listin ən yaygın olan bəzi metodlarını izah etmək maraqlı olar. İşte ən çox istifadə olunan bir neçəsi:

#### append(): Siyahının sonuna yeni bir element əlavə edir.
``` python
meyvelər = ["Alma", "Armud", "Nar"]
meyvelər.append("Üzüm")
print(meyvelər)  # ["Alma", "Armud", "Nar", "Üzüm"]

```
#### insert(): Verilən indeksə yeni bir element əlavə edir.
``` python 
meyvelər = ["Alma", "Armud", "Nar"]
meyvelər.insert(1, "Üzüm")
print(meyvelər)  # ["Alma", "Üzüm", "Armud", "Nar"]
```
#### remove(): Siyahıda verilən elementi silir.
```python
meyvelər = ["Alma", "Armud", "Nar"]
meyvelər.remove("Alma")
print(meyvelər)  # ["Armud", "Nar"]
```
#### pop(): Verilən indeksdəki elementi silir və onu qaytarır.
```python
meyvelər = ["Alma", "Armud", "Nar"]
silinən = meyvelər.pop(1)
print(silinən)   # "Armud"
print(meyvelər)  # ["Alma", "Nar"]
```
#### index(): Verilən elementin indeksini tapır.
```python
meyvelər = ["Alma", "Armud", "Nar"]
indeks = meyvelər.index("Nar")
print(indeks)  # 2
```

### count(): Verilən elementin siyahıda neçə dəfə təkrarlandığını hesablayır.
```python
meyvelər = ["Alma", "Armud", "Nar", "Alma"]
say = meyvelər.count("Alma")
print(say)  # 2
```

# Dovrler
 Python proqramlaşdırma dilində dövr strukturları haqqında ətraflı məlumat almaq istəyirsiniz. İki əsas dövr strukturu var: for və while. Hər ikisi də fərdi təkrarlanan əməliyyatları icra etməyə imkan verir, amma fərqli şərtlərə uyğun olaraq. Buna baxmayaraq, bir dövr növünün seçilməsi ümumi məqsədə və proqramın icrasına bağlı olacaq.

# For
`For` dövrü, bir sıra (məsələn, siyahı, tuple, set və s.) üzərində tək-tək elementləri dolaşmaq üçün istifadə olunur. Bu dövr, təkrarlar sayəsində hər bir element üçün bir blok kod icra edir.
``` python
siyahı = [1, 2, 3, 4, 5]
for element in siyahı:
    print(element)
```
Bu nümunədə, siyahı adlı siyahı dəyişənindəki hər bir elementi dolaşan for dövrü var. Hər bir element üçün, dövrün daxilində kod təkrarlanır və element konsola çap olunur.
# While
`while` dövrü, şərt ödənənə qədər bir blok kodu təkrarlar. Şərt doğru olduğu müddətdə, dövr icra olunacaq.

```python
n = 0
while n < 5:
    print(n)
    n += 1
```
Bu nümunədə, n dəyişəni 0-dan başlayır və hər dövrün sonunda 1 artırılır. Dövr, n dəyişəni 5-dən kiçik olduğu müddətdə icra olunacaq. Dövr icra olunarkən, əvvəlcədən tanımlanmış şərtlərin izlənilməsi vacibdir.

`while` dövrü zaman zaman sonsuz dövrə səbəb ola bilər, buna diqqət etmək vacibdir. Belə bir halda, proqramın icrasını dayandırmaq üçün nəzəri yollar mövcuddur (məsələn, break ifadəsi).

Dövr strukturları, Python-da proqramçılar üçün çox güclü alətlərdir və proqramların müxtəlif tələblərinə uyğun proqram kodu yazmağa kömək edir.

# Practice
Tapşırığın məzmunu:

Bir hissə mənfi ədədlərdən ibarət bir siyahı (list) verilir. Bu siyahıdakı ədədləri bir-biri ilə əvəz edərək həmin siyahının daxilindəki ədədlərin hamısını mənfi ədədlər edin.

Əlavə olaraq, bu əməliyyatı yerinə yetirmək üçün bir for və ya while dövrü istifadə edin.

Tapşırığın icrası üçün bəzi mərhələlər:

Mənfi ədədlərdən ibarət bir siyahı (list) yaradın. (Məsələn: [-2, 3, -5, 7, -11])
for və ya while dövrü vasitəsilə siyahıdakı hər bir ədədi yoxlayın.
Əgər ədəd mənfi ədəddirsə, onu müsbət ədədə əvəz edin.
Nəticə olaraq, siyahıda yalnız mənfi ədədlərin yerinə müsbət ədədlər qalacaq.
Nəticəni çap edin.
İşinizi bitirdikdən sonra, Python kodunuzu buraya paylaşa bilərsiniz və nəticəni yoxlaya bilərik!

#################################################################################
İstifadəçidən bir ədəd daxil etməsini tələb edən bir proqram yazın. Bu ədəd, "0" daxil olmaqla ədədlərin cəmi olacaq. Daha sonra istifadəçidən ədədləri daxil etməsi istənilir. Ədəd daxil edən müddətcə proqram ən son daxil olunan ədədlərin cəmini hesablayacaq. Əgər istifadəçi "0" daxil edərsə, proqram hesablamanı dayandıracak və ədədlərin cəmini ekrana çap edəcək.

Tapşırığın icrası üçün bəzi mərhələlər:

İstifadəçiyə "Zəhmət olmasa bir ədəd daxil edin (0-dan fərqli bir ədəd daxil edəsiniz, 0 daxil etdikdə hesablama başa çatır):" kimi bir mesaj göstərin.
İstifadəçinin daxil etdiyi ədədləri bir cüt dövr ilə oxuyun.
Hər dövrdə daxil edilən ədədi cəmə əlavə edin.
Əgər istifadəçi "0" daxil edərsə, dövrü dayandırın.
Nəticə olaraq, cəmi çap edin.
Əgər ədəd cəmi tapşırığı tamamladıqdan sonra, kodunuzu burada paylaşa bilərsiniz.












```python
siyahı = [-2, 3, -5, 7, -11]
index = 0

while index < len(siyahı):
    if siyahı[index] < 0:
        siyahı[index] *= -1
    index += 1

print("Nəticə:", siyahı)
```


```python
 #Əvvəlcədən cəmi və daxil edilmiş ədədləri yadda saxlamaq üçün dəyişənləri təyin edirik
cem = 0
eded = None

 #Ədədləri daxil etməyi tələb edirik və "0" daxil edilməsi halında dövrü dayandırırıq
while eded != 0:
    eded = int(input("Zəhmət olmasa bir ədəd daxil edin (0-dan fərqli bir ədəd daxil edəsiniz, 0 daxil etdikdə hesablama başa çatır): "))
    cem += eded

 #Nəticəni çap edirik
print("Daxil etdiyiniz ədədlərin cəmi:", cem)
```