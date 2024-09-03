
# HTML Ders Notu

---

## Giriş

HTML (HyperText Markup Language), web sayfalarını oluşturmak için kullanılan temel dildir. HTML, web tarayıcılarının içeriği anlamasını ve görüntülemesini sağlayan etiketlerden oluşur.

---

## HTML'in Temel Yapısı

Bir HTML belgesi şu şekilde yapılandırılmıştır:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Sayfa Başlığı</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, ilk HTML belgemizdir.</p>
</body>
</html>
```

- `<!DOCTYPE html>`: HTML5 belgesinin tanımıdır.
- `<html>`: Tüm HTML içeriğini saran kök etikettir.
- `<head>`: Sayfa hakkında meta bilgileri içerir (başlık, stil, meta etiketleri).
- `<title>`: Tarayıcı sekmesinde görünen başlıktır.
- `<body>`: Görüntülenen içeriği içerir (metin, resimler, bağlantılar vb.).

---

## Başlık Etiketleri

Başlık etiketleri, metinlerin hiyerarşik yapısını belirtmek için kullanılır. En büyük başlık `<h1>` ve en küçük başlık `<h6>` etiketidir.

```html
<h1>Bu Bir Başlıktır</h1>
<h2>Bu Bir Alt Başlıktır</h2>
```

---

## Paragraf Etiketi

Paragraflar, `<p>` etiketi ile belirtilir.

```html
<p>Bu bir paragraftır.</p>
```

---

## Bağlantı Etiketi

Bağlantılar, `<a>` etiketi ile oluşturulur. `href` özniteliği, bağlantının yönlendirileceği URL'yi belirtir.

```html
<a href="https://www.example.com">Bu bir bağlantıdır</a>
```

---

## Görüntü Etiketi

Resimler, `<img>` etiketi ile eklenir. `src` özniteliği, resim dosyasının yolunu belirtir ve `alt` özniteliği, resim yüklenemezse gösterilecek alternatif metni belirtir.

```html
<img src="resim.jpg" alt="Bir Resim">
```

---

## Liste Etiketleri

Sıralı ve sırasız listeler oluşturmak için `<ul>` (sırasız liste) ve `<ol>` (sıralı liste) etiketleri kullanılır. Liste öğeleri `<li>` etiketi ile tanımlanır.

```html
<ul>
    <li>Elma</li>
    <li>Muz</li>
    <li>Portakal</li>
</ul>

<ol>
    <li>Birinci</li>
    <li>İkinci</li>
    <li>Üçüncü</li>
</ol>
```

---

## Tablo Etiketleri

Tablolar, `<table>` etiketi ile oluşturulur. Satırlar `<tr>`, sütunlar `<td>` ve başlık hücreleri `<th>` etiketi ile belirtilir.

```html
<table>
    <tr>
        <th>Ad</th>
        <th>Soyad</th>
    </tr>
    <tr>
        <td>Ali</td>
        <td>Yılmaz</td>
    </tr>
</table>
```

---

## HTML Etiketlerinin Genel Özellikleri

- HTML etiketleri açılış (`<etiket>`) ve kapanış (`</etiket>`) etiketlerinden oluşur.
- Çoğu HTML etiketi içeriği düzenlemek için kullanılır.
- Etiketlerin büyük/küçük harf duyarlılığı yoktur, ancak küçük harf kullanımı yaygındır.

---

## Ders Notu Sonu

Bu ders notu, HTML'in temel kavramlarını anlamanızı sağlayacak temel bilgilere odaklanmaktadır. Daha ileri düzeyde HTML konuları için pratik yaparak ve ek kaynaklardan faydalanarak bilginizi genişletebilirsiniz.
