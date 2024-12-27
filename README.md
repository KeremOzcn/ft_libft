<p align="center">
  <img src="https://github.com/jotavare/jotavare/blob/main/42/banners/piscine_and_common_core/github_piscine_and_common_core_banner_ft_libft.png">
</p>

<p align="center">
	<img src="https://img.shields.io/badge/status-finished-success?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/badge/evaluated-27%20%2F%2010%20%2F%202024-success?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/badge/score-100%20%2F%20100-success?color=%2312bab9&style=flat-square" />
	<a href='https://www.linkedin.com/in/kerem0zcn' target="_blank"><img alt='Linkedin' src='https://img.shields.io/badge/LinkedIn-100000?style=flat-square&logo=Linkedin&logoColor=white&labelColor=0A66C2&color=0A66C2'/></a>
</p>

## Proje Açıklaması

`ft_libft` projesi, C dilindeki temel kütüphane fonksiyonlarını yeniden implementasyon etmeyi amaçlayan bir projedir. Bu proje, kütüphane fonksiyonlarını daha iyi anlamaya ve özelleştirilebilir bir şekilde yeniden oluşturmaya yöneliktir.

[Click here for the English version](README_EN.md)

## Dosya Yapısı

- `ft_atoi.c`: Bir dizgeyi tam sayıya dönüştüren fonksiyon.
- `ft_bzero.c`: Bellek alanını sıfırlayan fonksiyon.
- `ft_calloc.c`: Bellek alanı tahsis eden ve sıfırlayan fonksiyon.
- `ft_isalnum.c`: Alfanumerik bir karakter olup olmadığını kontrol eder.
- `ft_isalpha.c`: Alfabetik bir karakter olup olmadığını kontrol eder.
- `ft_isascii.c`: ASCII karakter aralığında olup olmadığını kontrol eder.
- `ft_isdigit.c`: Bir rakam olup olmadığını kontrol eder.
- `ft_isprint.c`: Yazdırılabilir bir karakter olup olmadığını kontrol eder.
- `ft_itoa.c`: Bir tamsayıyı dizgeye çevirir.
- `ft_memchr.c`: Bellek bloğunda bir karakter arar.
- `ft_memcmp.c`: İki bellek bloğunu karşılaştırır.
- `ft_memcpy.c`: Bellek bloğunu başka bir alana kopyalar.
- `ft_memmove.c`: Bellek bloklarını güvenli bir şekilde taşır.
- `ft_memset.c`: Bellek bloklarını belirli bir değerle doldurur.
- `ft_putchar_fd.c`: Bir karakteri belirtilen dosya tanımlayıcısına yazar.
- `ft_putendl_fd.c`: Bir dizgeyi yeni satırla birlikte belirtilen dosya tanımlayıcısına yazar.
- `ft_putnbr_fd.c`: Bir tamsayıyı belirtilen dosya tanımlayıcısına yazar.
- `ft_putstr_fd.c`: Bir dizgeyi belirtilen dosya tanımlayıcısına yazar.
- `ft_split.c`: Bir dizgeyi belirli bir ayraç ile böler.
- `ft_strchr.c`: Bir dizgede belirli bir karakter arar.
- `ft_strdup.c`: Bir dizgenin kopyasını oluşturur.
- `ft_striteri.c`: Her karakter üzerinde belirtilen işlevi çalıştırır.
- `ft_strjoin.c`: İki dizgeyi birleştirir.
- `ft_strlcat.c`: Dizgeleri birleştirirken toplam uzunluğu döner.
- `ft_strlcpy.c`: Dizgeyi kopyalarken toplam uzunluğu döner.
- `ft_strlen.c`: Bir dizgenin uzunluğunu döner.
- `ft_strmapi.c`: Her karakter üzerinde belirtilen işlevi çalıştırır ve yeni bir dizge döner.
- `ft_strncmp.c`: İki dizgeyi belirli bir uzunlukta karşılaştırır.
- `ft_strnstr.c`: Bir dizgede alt dizge arar.
- `ft_strrchr.c`: Bir dizgede son geçen belirli bir karakteri arar.
- `ft_strtrim.c`: Belirli karakterleri dizgenin başından ve sonundan kırpar.
- `ft_substr.c`: Bir dizgeden alt dizge oluşturur.
- `ft_tolower.c`: Büyük harfi küçük harfe çevirir.
- `ft_toupper.c`: Küçük harfi büyük harfe çevirir.
- `libft.h`: Fonksiyon prototiplerini ve makro tanımlamalarını içerir.
- `Makefile`: Projeyi derlemek için kullanılan betik dosyası.

## Kullanım

### Derleme

Projeyi derlemek için aşağıdaki komutları kullanabilirsiniz:

```bash
make
```

Bu komut, tüm dosyaları derleyerek bir `libft.a` kütüphanesi oluşturur.

### Kullanım Örneği

```c
#include "libft.h"

int main(void)
{
    char str[50] = "Merhaba Dünya!";
    ft_memset(str, '*', 5);
    printf("%s\n", str);
    return (0);
}
```

Bu kod, konsola şu sonucu yazdırır:

```
*****ba Dünya!
```

## Fonksiyon Prototipleri

Tüm fonksiyon prototipleri `libft.h` başlık dosyasında tanımlıdır. Örnek bir prototip:

```c
void *ft_memset(void *s, int c, size_t n);
```

### Parametreler
- `ft_memset`: Bellek bloğu, doldurma değeri ve uzunluğu belirtir.
- `ft_strcpy`: Kopyalanacak kaynak dizgi ve hedef dizi.
- `ft_strlen`: Uzunluğu hesaplanacak dizgi.

### Dönüş Değerleri
- `ft_memset`: Düzenlenmiş bellek bloğunu döner.
- `ft_strcpy`: Kopyalanan dizgiyi döner.
- `ft_strlen`: Dizginin uzunluğunu döner.

## Katkı

Katkıda bulunmak için lütfen bir "pull request" oluşturup projenizi paylaşın. Her türlü katkı ve geribildirim memnuniyetle karşılanır.
