---
layout: post
catagory: HTML
title: HTML Girişi
subtitle: HTML, web sayfaları oluşturmak için kullanılan standart işaretleme dili.
tags: [HTML]
---

# HTML Girişi
HTML, web sayfaları oluşturmak için kullanılan standart işaretleme dili.

## HTML nedir?
- HTML, Hyper Text Markup Language'ın kısaltmasıdır.
- HTML, web sayfaları oluşturmak için kullanılan standart işaretleme dilidir.
- HTML, bir web sayfasının yapısını tanımlar.
- HTML, bir dizi elementten oluşur.
- HTML elementleri, tarayıcıya içeriği nasıl görüntüleyeceğini söyler.
- HTML elementleri, "bu bir başlık", "bu bir paragraf", "bu bir bağlantı" gibi içerik parçalarını etiketler.

## Basit bir HTML Belgesi
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Sayfa Başlığı</title>
    </head>
    <body>
        <h1>İlk Başlığım</h1>
        <p>İlk paragrafım.</p>
    </body>
</html>
```

### Örnek Açıklaması
- `<!DOCTYPE html>` beyanı, bu belgenin bir HTML5 belgesi olduğunu tanımlar.
- `<html>` öğesi, bir HTML sayfasının kök öğesidir.
- `<head>` öğesi, HTML sayfası hakkında meta bilgileri içerir.
- `<title>` öğesi, HTML sayfası için bir başlık belirtir (bu başlık tarayıcının başlık çubuğunda veya sayfanın sekmesinde görüntülenir).
- `<body>` öğesi, belgenin gövdesini tanımlar ve başlıklar, paragraflar, resimler, bağlantılar, tablolar, listeler vb. gibi tüm görünür içeriklerin bir konteyneridir.
 - `<p>` öğesi, bir paragraf belirtir.

## Bir HTML öğesi nedir?
Bir HTML öğesi, bir başlangıç etiketi (start tag), bir içerik ve bir bitiş etiketi (end tag) ile tanımlanır.
### __`<etiketadı>` İçerik buraya yazılır... `</etiketadı>`__
The HTML __element__ is everything from the start tag to the end tag:
### __`<h1>`İlk Başlığım`</h1>`__
### __`<p>`İlk paragrafım.`</p>`__

| Başlangıç Etiketi | Öğe İçeriği | Bitiş Etiketi |
| - | - | - |
| `<h1>` | İlk Başlığım | `</h1>` |
| `<p>` | İlk Paragrafım. | `</p>` |
| `<br>` | Hiçbiri | Hiçbiri |

> **Not:**  Bazı HTML öğelerinin içeriği yoktur (örneğin `<br>` öğesi gibi). Bu öğelere boş öğeler denir. Boş öğelerin bir bitiş etiketi yoktur!