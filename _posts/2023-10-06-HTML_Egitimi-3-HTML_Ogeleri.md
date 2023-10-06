---
layout: post
catagory: HTML
title: HTML Öğeleri
subtitle: Bir HTML öğesi, bir başlangıç ​​etiketi, bazı içerikler ve bir son etiket ile tanımlanır.
tags: [HTML]
---

# HTML Öğeleri
Bir HTML öğesi, bir başlangıç ​​etiketi, bazı içerikler ve bir son etiket ile tanımlanır.

## HTML Öğeleri
HTML **elementi** başlangıç etiketinden bitiş etiketine kadar olan her şeydir:
### `<etiketadı>`**İçerik buraya yazılır...**`</etiketadı>`
Bazı HTML elementlerinin örnekleri:
### `<p>`**İlk Başlığım**`</p>`
### `<p>`**İlk paragrafım.**`</p>`

| Başlangıç etiketi| Eleman içeriği | Bitiş etiketi |
| - | - | - |
| `<h1>` | Benim İlk Başlığım | `</h1>` |
| `<p>` | İlk paragrafım | `</p>` |
| `<br>` | Yok | Yok |

**Not**: Bazı HTML elementlerinin içeriği yoktur (örneğin `<br>` elementi gibi). Bu elementlere boş elementler denir. Boş elementlerin bir bitiş etiketi yoktur!

# İç içe geçmiş HTML Elementleri 
HTML elementleri iç içe geçebilir (bu, elementlerin diğer elementleri içerebileceği anlamına gelir).  
Tüm HTML belgeleri iç içe geçmiş HTML elementlerinden oluşur.  
Aşağıdaki örnek dört HTML elementi içerir (`<html>`, `<body>`, `<h1>` ve `<p>`):

 #### ÖRNEK 
 ```html
<!DOCTYPE html>
<html>
    <body>
        <h1>Benim İlk Başlığım</h1>
        <p>Benim ilk paragrafım.</p>
    </body>
</html>
```

## Örnek Açıklaması

`<html>` elementi kök elementtir ve tüm HTML belgesini tanımlar.  
Başlangıç etiketi `<html>`, bitiş etiketi ise `</html>`'dir.  
Ardından, `<html>` elementi içinde bir `<body>` elementi bulunur:  
`<body>`  
`<h1>`Benim İlk Başlığım`/h1>`  
`<p>`Benim ilk paragrafım.`</p>`  
`</body>`  
`<body>` elementi belgenin gövdesini tanımlar.  
Başlangıç etiketi `<body>`, bitiş etiketi ise `</body>`'dir.  
Ardından, `<body>` elementi içinde iki başka element bulunur: `<h1>` ve `<p>`:

```html
<h1>Benim İlk Başlığım</h1>
<p>Benim ilk paragrafım.</p>
```

`<h1>` elementi bir başlık tanımlar.  
Başlangıç etiketi `<h1>`, bitiş etiketi ise `</h1>`'dir:

```html
<h1>Benim İlk Başlığım</h1>
```

`<p>` elementi bir paragraf tanımlar.  
Başlangıç etiketi `<p>`, bitiş etiketi ise `</p>`'dir:

```html
<p>Benim ilk paragrafım.</p>
```

## Asla Bitiş Etiketini Atlama
Bazı HTML elementleri, bitiş etiketini unutsanız bile doğru şekilde görüntülenebilir:

#### ÖRNEK
```html
<html>
    <body>
        <p>Bu bir paragraf
        <p>Bu bir paragraf
    </body>
</html>
```

**Ancak buna asla güvenmeyin! Eğer bitiş etiketini unutursanız beklenmedik sonuçlar ve hatalar meydana gelebilir!**

## Boş HTML Elementleri
İçeriği olmayan HTML elementlerine boş elementler denir.  
`<br>` etiketi bir satır sonu tanımlar ve kapanış etiketi olmadan bir boş elementtir:

#### ÖRNEK 
```html
<p>Bu bir <br> satır sonu olan paragraftır.</p>
```

## HTML Büyük-Küçük Harfe Duyarlı Değildir
HTML etiketleri büyük-küçük harfe duyarlı değildir: `<P>`, `<p>`'yle aynı anlamı taşır.  
HTML standardı küçük harfli etiketleri zorunlu tutmaz, ancak W3C, HTML için küçük harfleri **önerir** ve XHTML gibi daha katı belge tipleri için küçük harfleri **zorunlu kılar**.