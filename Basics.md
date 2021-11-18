[← go back/menü](./README.md)

# Basics
yani en basitler

**İçindekiler**
- Fonksiyonlar
- String
- Sayılar
- Değişkenler

---

### Notlar

**Noktalı Virgül (`;`):** JS'de yazmasan da çalışır ama yazman daha iyi olur çünkü diğer dillere geçerken yardımcı olur ve de kodunu daha güzel gösterir

---

### Fonksiyonlar

Bu çok önemli birşey, çünkü yapacağın neredeyse herşeyde en az bir tane fonksiyon vardır.

Fonksiyonlar aslında kendileri de bir dize koddur

ℹ️ Bir fonksiyonu çalıştırmak için isminin yanına iki parantez `()` ekliyorsun

ℹ️ Bu iki parantezin içine de fonksiyonun arguments/argümanlarını (ek şeyler) yazabilirsin

ℹ️ Argümanlar virgül ile ayrılır

⚠️ Virgüllü/kesir sayı için bu yüzden JS'de virgül yerine nokta konulur (örn `1.6`)

**Örnek**
`console.log`, konsola birşey yazdırmanın fonksiyonudur, hadi konsola "Selam" yazalım

```js
console.log("Selam");
```

Gördüğün gibi parantezin içine `"Selam"` yazdım, bu bir argümandır

```js
havaliBisey(1, 2, 3)
```

Buradada 3 tane argümanı olan bir fonksiyon var (ve evet ismi `havaliBisey`)

---

### String (Yazı)

String, yazıdır bu kadar lmao

ℹ️ JS'de string yapmak için yazını `"` (çift tırnak, iki tane tek tırnak değil!) veya `'` karakterleri ile başlat ve bitir

❗ *Stringime `"`/`'` koymak istiyorum!:* Stringini ya diğer karakter ile başlat ve bitir ya da `"`'dan önce `\` yaz

**Örnek**

- `merhaba"` ❌
- `"merhaba"` ✅
- `'merhaba'` ✅
- `"merhaba'` ❌
- `""uwu" desene"` ❌
- `'"uwu" desene'` ✅
- `"\"uwu\" desene"` ✅

---

### Sayılar

sadece yazardan çalışıyo bişe yapmana gerek yok

ha sadece virgüllü sayılar için nokta kullan

- `1`
- `24`
- `31.31`
- `187272`

---

### `undefined`

`undefined` bir değer verilmemiş demek, boş gibi

---

## Yorumlar (Comment)

JS yorumları görmezden gelir

Kodun herhangi bir yerinde `//` ile yazarsan ondan sonra o satırda yorum olur

Birden fazla satırlık yorum istiyorsan yorumunu `/*` ile başlat ve `*/` ile bitir

**Örnek**
```js
// İsmi konsola yaz
console.log(reis); // örnek yorum bla bla

/* birden
fazla
satır.
*/

// hata verdiği için commentledim bla bla
//console.log(xdxd);
```

---

## Değişkenler

Değişkenler 3 şekilde belirlenebilir:
- `var` ile
- `let` ile
- `const` ile

> biz `let`'i kullanmayacağız çünkü artık standartta değil
> yani onu görürseniz `let` fonksiyonu gördüğünü sanabilirsiniz

Ve bu ikisinin tek bir farkı var: `const` değişkeni değiştirememeni sağlıyor yani asla değişmez

ℹ️ Bir değişken belirlemek için `let` (yada `const`), boşluk ve değişkenin adını yazıyorsun

ℹ️ `=` kullanarak değişkeni belirtirken aynı zamanda ona bir değer verebilirsin (`const` kullanırsan gerekli)

ℹ️ Daha önce belirlediğin bir değişkenin ismini yazıp `=` ile ona yeni birşey verebilirsin

**Örnekler**

```js
let isim = "Ashley";

let age;

age = 3; // bebe

const blackLivesMatter = true;
// değiştiremezsin ağla
```

> aslında let yada const yazmazsan da çalışır ama bozulma ihtimali çok yüksek lol

---

## Değişkenlerle oynamak

yani operatörler! ✨

- `+`:
   - string ve string: ikisini birleştirir
   - string ve sayı: üstteki ile aynı, sayıyı stringe dönüştürür
   - sayı ve sayı: toplama yapar
- `-`, `*`, `/`: matematik işlemleri yapar, string varsa numara yapmaya çalışır

ℹ️ Bu operatörlerde değişken ismini yada değerini kullanabilirsin

ℹ️ Bunların yanına bir `=` eklersen o işlemi o değişkenle yapıp ekler

**Örnekler**

```js
let a = 1;

a + 8 // 9 verir

let b = 5;

b - a // 4 verir

b -= a; // b artık 4
b = b - a; // bir üstteki ile aynı
```

```js
let isim = "buwak";
let mesaj = "merhaba " + isim + ", çok tatlısın";

console.log(mesaj); // "merhaba buwak, çok tatlısın"

console.log("selam " + isim); // "selam buwak"
```

---

📜 [← Menü](./README.md)

➡️ [Basics 2](./Basics2.md)
