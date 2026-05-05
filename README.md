​✨ Özəlliklər
​Təhlükəsiz Giriş Sistemi: * İstifadəçi adı və şifrə ilə doğrulama.
​3 dəfə yanlış şifrə daxil edildikdə 10 saniyəlik müvəqqəti bloklanma.
​Məlumatların Qalıcılığı: * İstifadəçilər, məhsullar və səbətlər JSON fayllarında saxlanılır.
​Hər bir əməliyyat (giriş, məhsul əlavə etmə, alış-veriş) .log fayllarında tarix və saatla qeyd olunur.
​Alış-veriş Məntiqi:
​Kateqoriyalar üzrə məhsul seçimi.
​Səbətə əlavə etmə və balansın yoxlanılması ilə "Checkout" (ödəniş) sistemi.
​Balans yetərli olmadıqda xəbərdarlıq sistemi.
​🛠 Texnologiyalar
​Dil: Python 3.x
​Kitabxanalar: json, os, time, datetime
​📂 Fayl Strukturu
​main.py - Əsas proqram kodu.
​users.json - İstifadəçi məlumatları və balanslar.
​products.json - Mövcud məhsullar və qiymətlər.
​basket_[istifadəçi].json - Hər istifadəçiyə özəl aktiv səbət faylı.
​history_[istifadəçi].log - İstifadəçinin sistemdəki hərəkət tarixçəsi.

İstifadə Qaydası
​Giriş: Defolt olaraq akif (şifrə: 123) və ya nuray (şifrə: 456) hesablarından istifadə edə bilərsiniz.
​Mağaza: Kateqoriya seçin, məhsulun ID-sini daxil edin və miqdarı qeyd edib 'b' düyməsi ilə səbətə atın.
​Ödəniş: Səbət bölməsinə keçib checkout yazaraq alışı tamamlayın. Bu zaman məbləğ balansınızdan çıxılacaq.
​⚠️ Qeydlər
​Sistem real vaxt rejimində JSON fayllarını yeniləyir, buna görə də proqramı bağlayıb açdıqda balansınız və səbətiniz qorunub saxlanılır.
​Təhlükəsizlik məqsədilə ardıcıl yanlış girişlər zamanı proqram time.sleep() funksiyası ilə gözləmə rejiminə keçir.
