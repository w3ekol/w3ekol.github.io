---
layout: post
catagory: HTML
title: HTML Temel Örnekler
subtitle: Bu bölümde bazı temel HTML örnekleri göstereceğiz. Henüz öğrenmediğiniz etiketleri kullanırsak endişelenmeyin.
tags: [HTML]
---

# HTML Temel Örnekler
Bu bölümde bazı temel HTML örnekleri göstereceğiz.
Henüz öğrenmediğiniz etiketleri kullanırsak endişelenmeyin.

## HTML Belgeleri
Tüm HTML belgeleri, bir belge türü bildirimiyle başlamalıdır:`<!DOCTYPE html>`
HTML belgesi kendisi `<html>` ile başlar ve `</html>` ile biter.
HTML belgesinin görünen kısmı `<body>` ve `</body>` arasındadır.

### Örnek:
```html
<!DOCTYPE html>
<html>
    <body>
        <h1>İlk Başlığım</h1>
        <p>İlk paragrafım.</p>
    </body>
</html>
```

## <!DOCTYPE> Beyanı
`<!DOCTYPE>` beyanı, belge türünü temsil eder ve tarayıcıların web sayfalarını doğru şekilde görüntülemesine yardımcı olur.
Sadece bir kez, sayfanın en üstünde (herhangi bir HTML etiketinden önce) görünmelidir.  
`<!DOCTYPE>` beyanı büyük-küçük harf duyarlı değildir.
HTML5 için `<!DOCTYPE>` beyanı şu şekildedir:

## HTML Başlıkları
HTML başlıkları, `<h1>` ile `<h6>` etiketleriyle tanımlanır.
`<h1>,` en önemli başlığı tanımlar. `<h6>,` en az önemli başlığı tanımlar:

### Örnek: 
`<h1>`Bu başlık 1`</h1>`  
`<h2>`Bu başlık 2`</h2>`  
`<h3>`Bu başlık `</h3>`  

## HTML Paragrafları
HTML paragrafları .`</p>` etiketi ile tanımlanır:

### Örnek:
`<p>`Bu bir paragraftır.`</p>`  
`<p>`Bu başka bir paragraftır`</p>`  

## HTML Bağlantıları
HTML links are defined with the`<a>` tag:

### Örnek:
```html
<a href="https://www.w3ekol.com">Bu bir bağlantıdır</a>
```

Bağlantının hedefi `href` özniteliğinde belirtilir. Öznitelikler, HTML öğeleri hakkında ek bilgiler sağlamak için kullanılır.
Öznitelikler hakkında daha fazla bilgiyi daha sonraki bir bölümde öğreneceksiniz.

## HTML Görselleri (Resimler)
HTML resimleri, `<img>` etiketiyle tanımlanır.
Kaynak dosya `(src),` alternatif metin `(alt)`, genişlik `(width)` ve yükseklik `(height)` öznitelikler olarak sağlanır:

### Örnek:
```html
<img src="w3ekol.jpg" alt="w3ekol.com" width="104" height="142">
```

## HTML Kaynağını Görüntüleme
Hiçbir web sayfasını gördünüz mü ve 'Hey! Bunları nasıl yaptılar?' diye merak ettiniz mi?

### HTML Kaynak Kodunu Görüntüle:
Bir HTML sayfasında sağ tıklayın ve "Sayfa Kaynağını Görüntüle" (Chrome'da) veya "Kaynağı Görüntüle" (Edge'de) gibi benzer bir seçeneği seçin. Bu, sayfanın HTML kaynak kodunu içeren bir pencere açacaktır.

### Bir HTML Öğesini Denetle:
Bir öğeye (veya boş bir alana) sağ tıklayın ve "Denetle" veya "Öğeyi Denetle" seçeneğini seçerek öğelerin nasıl oluşturulduğunu görmek için HTML ve CSS'yi görebilirsiniz. Ayrıca, açılan Denetim veya Stil panelinde HTML veya CSS'yi anında düzenleyebilirsiniz.