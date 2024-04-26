# Python funksiyalari

Python-da funksiyalar özündə bir neçə əməliyyatları birləşdirən, təkrarlanan kod hissələrini
özündə cəmləyən proqram hissələridir.
Funksiyaları istifadə edərək kodu daha təkmilləşdirə və daha asan oxuna bilərsiniz.
indi, bir funksiya necə yaradılır və istifadə olunur:

```python
# Funksiya yaradırıq
def salam_ver():
    print("Salam, dünya!")

# Funksiyani çağırırıq
salam_ver()
```

Bu kodda, salam_ber adlı bir funksiya yaradırıq və onu print funksiyası ilə "Salam, dünya!" metnini çap edəcək şəkildə təyin edirik. Sonra, funksiyamızı salam_ber() ilə çağırırıq və konsola "Salam, dünya!" yazısını çap edirik

Funksiyalar istədiyiniz qədər müxtəlif olabilir və parametrlər qəbul edə bilər. Məsələn:

```python
# Funksiyaya parametr əlavə edərək
def salam_ver():
    print("Salam, " + name + "!")

# Funksiyani çağırarkən parametr göndəririk
salam_ber("Mehman")
```

Bu kodda, salam_ber funksiyası bir isim parametri qəbul edir. Sonra, funksiyamızı çağırarkən "Mehman" adlı parametri göndəririk və konsola "Salam, Mehman!" yazısını çap edirik.

Python funksiyaları kodunuzu daha quraşdırılmış və oxunması asan hala gətirir, buna görə də onların istifadəsi çox vacibdir.

Çap: Funksiyalar, print kimi hazır funksiyalar vasitəsilə məlumatları çap edə bilər.

Qaytarılan Dəyərlər: Funksiyalar, hesablama nəticəsini geri qaytarmaq üçün return ifadəsindən istifadə edə bilər.

```python
def topla(a, b):
    c = a + b
    return c
```

Yerli və Global Dəyişənlər: Funksiya daxilində tanımlanan dəyişənlər yalnız o funksiya daxilində işləyir. Amma global dəyişənlər proqramın hər yerində istifadə oluna bilər.

Anonim Funksiyalar (lambda): lambda ifadəsi ilə qısa və anonim funksiyalar yaradıla bilər.

```python
ikiyedox = lambda x: x * 2
print(ikiyedox(5))  # Çıxış: 10
```

Daxili Funksiyalar: Bir funksiya digər bir funksiya daxilində tanımlana bilər

```python
def parent_funksiya():
    def child_funksiya():
        print("Bu daxili funksiya işləyir.")
    child_funksiya()
```

Python-daki funksiyalar, kodun oxunması, idarə olunması və təkrarlanması üçün güclü bir alətdir. Bu mövzuda daha dərin bilik əldə etmək üçün Python rəsmi sənədlərinə və kitablarına baxa bilərsiniz.

# Practice

Tapşırıq: İki ədəd arasındakı bütün ədədlərin cəmini hesablayan bir funksiya yazın.

Tapşırıq: Verilmiş bir ədədin faktorialını hesablayan bir funksiya yazın.

Tapşırıq: İstifadəçinin daxil etdiyi ədədin ədədin mükəmməli olub-olmadığını yoxlayan bir funksiya yazın.

Tapşırıq: İstifadəçinin daxil etdiyi mətnin tərsinə çevrilmiş formasını qaytaran bir funksiya yazın.
