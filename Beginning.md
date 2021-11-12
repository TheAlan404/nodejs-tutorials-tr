# Başlangıç

[← Go Back](./README.md) i want to become monkey

İçindekiler
===========
- [Kurulum](#Kurulum)
- [İlk Projeni Oluşturma](#İlk Projeni Oluşturma)



## Kurulum

üşendim, her platform için farklı vs, genellikle [Nodejs'in sitesinden](https://nodejs.org) olur

nodejs'in yanında kodun kendisini yazmak için bir editöre ihtiyacın var.
bunun için bence en iyisi [Notepad++](https://notepad-plus-plus.org/downloads/) çünkü hataları anlamanız iyileşiyor ve bilgisayardan aşırı yardım almadan (😤 vscode) kodlamayı öğreniyorsunuz
ama başka alternatifler de var;
- VSCode: baya iyi ama performansı çok kötü. [Electron](./404.md) üzerinden yapıldığı için
- [nano](https://www.nano-editor.org/download.php): cmd/terminal'de hızlıca aşırı lightweight bir editör
- notepad.exe: ...cidden windowsun normal notepad'i
- vb, yazı editleyebilsin yeter

## İlk Projeni Oluşturma

**Kurmak için;**

1. Projen için bir klasör aç

> Bu şekilde dosyalar örn. masaüstünde kirlilik yapmaz ve daha düzenlidir

2. Klasörün içine gir ve bir dosya yarat

> ⚠️ `.js` ile bitmeli, `.txt` değil. aynı zamanda boşluksuz olur ise kendini işkenceden kurtarmış olursun.
> bu dosyanın içine kodun kendisini yazıcaksın

**Peki nası başlatcam bu şeyi??**

1. O klasörde bir terminal/cmd aç.

> **Windows**: Klasörde dosyanın olmadığı boş bir yerde (yeni klasör açıyomuş gibi)
> *Shift*'e basılı tutarak sağ tıkla, yeni çıkan seçeneğe bas. ('Burada Komut istemini aç' vs)
> eğer PowerShell (🤢) çıkıyorsa PowerShell'e `start cmd` yazıp cmd'ye geçebilirsin.

2. Bu komutu yaz: `node <dosya adı>`

> Eğer dosya adı vermezsen (`node`) nodejs'i interpreter yani deney vb modunda kullanırsın
> Nodejs, ona söylediğin dosyayı okuyup JS olarak çalıştırıcak
> örn; `node bot.js`

**Nası durdurcam lannn**

`ctrl+c` çoğu programı cmd'de durdurur/kapatır.
(nano hariç lol)

[← readme/go bakc](./README.md)

[Okumaya dewam: JavaScript Basics](./Basics.md)
