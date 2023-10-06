---
layout: post
catagory: HTML
title: HTML Özellikleri
subtitle: HTML özellikleri, HTML elementleri hakkında ek bilgi sağlar.
tags: [HTML]
---

# HTML Özellikleri
HTML özellikleri, HTML elementleri hakkında ek bilgi sağlar.

## HTML Özellikleri
- Tüm HTML elementleri **özelliklere** sahip olabilir
- Özellikler elementler hakkında **ek bilgi** sağlar
- Özellikler her zaman **başlangıç etiketinde** belirtilir
- Özellikler genellikle isim/değer çiftleri olarak gelir, örneğin:**isim="değer"**


## href Özelliği
`<a>` etiketi bir bağlantı tanımlar. `href` özelliği bağlantının gittiği sayfanın URL'sini belirtir:

#### ÖRNEK
```html
 <a href ="https://www.w3ekol.com">W3Ekol'u Ziyaret Et</a>
```

## src Özelliği
`<img>` etiketi, bir HTML sayfasına bir resim yerleştirmek için kullanılır. `src` özelliği görüntülenecek resmin yolunu belirtir:

#### ÖRNEK
```html
<img src="test.jpg">
```

**src** özelliğinde URL belirtmenin iki yolu vardır:  
**1. Mutlak URL** - Diğer bir web sitesinde barındırılan harici bir resme bağlantı sağlar. Örnek: `src="https://www.w3ekol.com/images/test.png"`.  
**Notlar:** Harici resimler telif hakkı altında olabilir. İzni almadan kullanırsanız, telif hakkı yasalarını ihlal edebilirsiniz. Ayrıca, harici resimleri kontrol edemezsiniz; aniden kaldırılabilir veya değiştirilebilir.  
**2. Göreli URL** - Web sitesi içinde barındırılan bir resme bağlantı sağlar. Burada URL, alan adını içermez. URL bir eğik çizgi olmadan başlarsa, mevcut sayfaya göre göreceli olur. Örnek: src="test.jpg". URL bir eğik çizgi ile başlıyorsa, alan adına göre göreceli olur. Örnek: src="/images/test.jpg".  
**İpucu:** Genellikle göreli URL'lerin kullanılması en iyisidir. Alan adını değiştirirseniz bağlantılar bozulmaz."

## width ve height Özellikleri
`<img>` etiketi ayrıca resmin `width` ve ` height ` belirten genişlik ve yükseklik özelliklerini içermelidir (piksel cinsinden):

#### ÖRNEK
```html
<img src="img_girl.jpg" width="500" height="600">
```

## alt Özelliği
`<img>` etiketi için gerekli olan `alt` özelliği, resmin herhangi bir nedenden dolayı görüntülenemediğinde bir alternatif metin belirtir. Bu, yavaş bir bağlantı, `src` özelliğindeki bir hata veya kullanıcının bir ekran okuyucu kullanması gibi durumlarda olabilir.

#### ÖRNEK
```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

#### ÖRNEK
 ```html
<img src="img_typo.jpg" alt="Girl with a jacket">
```

## style Özelliği
`style` özelliği, bir öğeye renk, yazı tipi, boyut ve daha fazlası gibi stiller eklemek için kullanılır.

#### ÖRNEK
```html
<p style="color:red;">Bu kırmızı bir paragraftır.</p>
```

## lang Özelliği
Her zaman web sayfasının dilini bildirmek için `lang` özelliğini `<html>` etiketi içine dahil etmelisiniz. Bu, arama motorlarına ve tarayıcılara yardımcı olmak için yapılır.  
Aşağıdaki örnek İngilizce'yi dil olarak belirtiyor:

```html
<!DOCTYPE html>
<html lang="en">
    <body>
    ...
    </body>
</html>
```

Ülke kodları, `lang` özelliğinde dil koduna ek olarak eklenir. Bu durumda, ilk iki karakter HTML sayfasının dilini tanımlar ve son iki karakter ülkeyi tanımlar.  
Aşağıdaki örnek İngilizce'yi dil ve Amerika Birleşik Devletleri'ni ülke olarak belirtiyor:

```html
!DOCTYPE html>
<html lang="en-US">
    <body>
    ...
    </body>
</html>
```

## title Özelliği
`title` özelliği bir element hakkında ekstra bilgi sağlar.  
`title` özelliğinin değeri, elementin üzerine fareyle geldiğinizde bir ipucu olarak görüntülenir:


#### ÖRNEK 
```html
<p title="Ben bir ipucuyum">Bu bir paragraftır.</p>
```

## Önerimiz: Her Zaman Küçük Harfli Özellikler Kullanın
HTML standardı küçük harfli özellik adları kullanımını zorunlu tutmaz.  
Title özelliği (ve diğer tüm özellikler), baş harfi büyük veya küçük olarak yazılabilir, yani **title** veya **TITLE** olabilir.  
Ancak, W3C, HTML için küçük harfli özellikleri **önerir** ve XHTML gibi daha katı belge tipleri için küçük harfli özelliklerin kullanılmasını **talep eder**.

## Önerimiz: Her Zaman Özellik Değerlerini Tırnak İçine Alın
HTML standardı özellik değerlerinin etrafında tırnak kullanımını zorunlu tutmaz.  
Ancak, W3C, HTML için tırnak kullanımını **önerir** ve XHTML gibi daha katı belge tipleri için tırnak kullanımını **talep eder**.

#### İyi
```html
<a href="https://www.w3ekol.com/html/">HTML rehberimize göz atın</a>
```

#### Kötü
```html
<a href=https://www.w3ekol.com/html/>HTML rehberimize göz atın</a>
```

Bazı durumlarda tırnak kullanmanız gerekebilir. Bu örnek, bir boşluk içerdiği için title özelliğini doğru bir şekilde göstermeyecektir:

#### ÖRNEK
```html
<p title=Hakkında W3ekol>
```

## Tek mi Yoksa Çift Tırnak mı?
HTML'de özellik değerlerini çevreleyen çift tırnaklar en yaygın olanıdır, ancak tek tırnaklar da kullanılabilir.  
Bazı durumlarda, özellik değeri kendisi çift tırnak içeriyorsa, tek tırnak kullanmak gereklidir:

```html
<p title='John "ShotGun" Nelson'>
```

Ya da tersi:

```html
<p title="John 'ShotGun' Nelson">
```

## Bölüm Özeti
- Tüm HTML elementleri **özelliklere** sahip olabilir.
- `<a>` etiketinin `href` özelliği bağlantının gittiği sayfanın URL'sini belirtir.
- `<img>` etiketinin `src` özelliği görüntülenecek resmin yolunu belirtir.
- `<img>` etiketinin `width` ve `height` özellikleri resimler için boyut bilgisi sağlar.
- `<img>` etiketinin `alt` özelliği bir resim için alternatif metin sağlar.
- `style` özelliği bir elemente renk, font, boyut gibi stiller eklemek için kullanılır.
- `<html>` etiketinin `lang` özelliği web sayfasının dilini belirtir.
- `title` özelliği bir element hakkında ekstra bilgi sağlar.