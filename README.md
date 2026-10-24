<!-- Wenitor Python Runner • animated README -->
<div align="center">

<a href="https://github.com/burakdevv/WenitorRunnerPython">
  <img src="https://uploads.onecompiler.io/44fx9epuv/1792876807498/899f1d72-eb71-417a-941a-2a9d398b75cd.png" alt="Wenitor Python Runner" width="260">
</a>

# Wenitor Python Runner

[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![WPF](https://img.shields.io/badge/UI-WPF-68217A?style=for-the-badge&logo=dotnet)](https://learn.microsoft.com/dotnet/desktop/wpf/)
[![C Sharp](https://img.shields.io/badge/language-C%23-239120?style=for-the-badge&logo=csharp)](https://learn.microsoft.com/dotnet/csharp/)
[![Python](https://img.shields.io/badge/Python-runner-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)](https://www.python.org/)

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=38BDF8&center=true&vCenter=true&width=720&lines=Python+kodunu+yaz%2C+calistir+ve+hata+ayikla;Kod+editoru+%2B+Python+Runner+%2B+Terminal;Wenitor+ile+uretkenligini+tek+ekranda+tut" alt="Animasyonlu Wenitor tanıtımı">

**Python kodunu yaz, gerçek Python yorumlayıcısıyla çalıştır ve geliştirme akışını tek pencerede yönet.**

[Özellikler](#-özellikler) · [Kurulum](#-kurulum) · [Kullanım](#-kullanım) · [Teknoloji](#-teknoloji)

</div>

---

## ✨ Wenitor nedir?

**Wenitor Python Runner**, Windows için tasarlanan koyu temalı bir Python geliştirme ortamıdır. Kod editörü, Python çalıştırıcısı, terminal ve proje dosyalarını tek bir masaüstü arayüzünde bir araya getirmeyi hedefler.

> Proje deposunda şu an yalnızca temel bir tanım yer alıyor. Bu README, Wenitor'un hedeflenen kullanımını tanıtır; listelenen işlevlerin kullanılabilirliği yayımlanan sürüme bağlıdır.

## 🚀 Özellikler

| Alan | Özellikler |
|---|---|
| **Kod editörü** | Python sözdizimi renklendirme, satır numaraları, otomatik girinti, çoklu sekmeler |
| **Python Runner** | Ayrı Python sürecinde betik çalıştırma, durdurma, standart çıktı ve hata yakalama |
| **Terminal** | Program çıktısı, hata mesajları ve çalışma durumu |
| **Proje gezgini** | Dosya ve klasörleri görüntüleme, .py dosyalarını açma ve kaydetme |
| **Geliştirme araçları** | Breakpoint/debug akışı, otomatik tamamlama ve pip paket yönetimi |
| **Arayüz** | WPF masaüstü arayüzü ve koyu tema |

## 🖥️ Ekran görüntüsü

Uygulamanın güncel ekran görüntüsünü eklemek için docs/images/screenshot.png dosyasını depoya ekleyip aşağıdaki satırı etkinleştir:

<!-- ![Wenitor Python Runner ekran görüntüsü](docs/images/screenshot.png) -->

## 📦 Kurulum

### Hazır Windows kurulumu

GitHub Releases bölümünde yayımlanmış bir kurulum paketi varsa en güncel Windows dosyasını indirip çalıştır.

[GitHub Releases sayfası](https://github.com/burakdevv/WenitorRunnerPython/releases)

### Kaynak koddan

Kaynak koddan derleme yönergeleri, proje dosyaları yayımlandığında buraya eklenecektir. Hedef teknoloji yığını **WPF, C# ve .NET 10**'dur.

## ▶️ Kullanım

1. Wenitor'u aç ve bir Python dosyası oluştur veya proje gezgininden .py dosyası aç.
2. Kodunu editörde yaz.
3. **Çalıştır** düğmesiyle etkin dosyayı çalıştır.
4. Çıktıyı ve hata ayrıntılarını terminal panelinde incele.
5. Gerekirse çalışmayı **Durdur** düğmesiyle sonlandır.

### Hızlı deneme

Bu örnek, Python yorumlayıcısını ve terminal çıktısını kontrol eder:

~~~python
from datetime import datetime
import sys

print("Merhaba, Wenitor!")
print(f"Python: {sys.version.split()[0]}")
print(f"Çalışma zamanı: {datetime.now():%Y-%m-%d %H:%M:%S}")

for adim in range(1, 4):
    print(f"İşlem {adim}/3 tamamlandı")
~~~

## 🧰 Teknoloji

- **Masaüstü arayüzü:** WPF, XAML ve C#
- **Hedef platform:** Windows 10 / Windows 11
- **Hedef .NET:** .NET 10
- **Python çalıştırma yaklaşımı:** ayrı Python süreci; stdout ve stderr yakalanır
- **Paket yönetimi:** Python pip

Python yorumlayıcısı, hedef bilgisayarda kurulu bir Python dağıtımı veya uygulamayla birlikte sağlanan bir dağıtım üzerinden yapılandırılmalıdır.

## 🗺️ Geliştirme hedefleri

- [x] Kod yazma ve Python dosyalarını yönetme
- [x] Python sürecini çalıştırma ve durdurma
- [x] Terminalde standart çıktı ve hata gösterimi
- [x] Çoklu dosya sekmeleri ve proje gezgini
- [x] Python renklendirme ve otomatik girinti
- [x] Breakpoint/debug desteği
- [x] Otomatik tamamlama ve pip paket yönetimi

## 🤝 Katkı

Hata bildirimi, fikir ve katkılar için [Issues](https://github.com/burakdevv/WenitorRunnerPython/issues) ve [Pull requests](https://github.com/burakdevv/WenitorRunnerPython/pulls) sayfalarını kullanabilirsin.

## 📄 Lisans

Depoda lisans dosyası yayımlandığında lisans bilgisi burada belirtilecektir. Lisans eklenene kadar kullanım ve yeniden dağıtım koşulları için depo sahibine danış.

---

<div align="center">

**Wenitor Python Runner** · Python geliştirme akışın için tek pencere.

[GitHub deposu](https://github.com/burakdevv/WenitorRunnerPython)

</div>
