---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection metodu. Belirtilen konumda koleksiyona boş bir sayfa ekleyin. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık rastlanan sayfanın boyutu seçilecektir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılacaktır.
type: docs
weight: 160
url: /tr/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Belirtilen konumda koleksiyona boş bir sayfa ekleyin. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık rastlanan sayfanın boyutu seçilecektir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılacaktır.

```csharp
public Page Insert(int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Yeni sayfanın konumu. |

### Dönüş Değeri

Eklenen sayfa.

### Ayrıca Bakınız

* sınıf [Page](../../page/)
* sınıf [PageCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Sayfayı belirtilen yere sayfa koleksiyonuna ekler.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Koleksiyondaki gerekli sayfa indeksi. |
| entity | Page | Eklenmesi gereken sayfa. |

### Dönüş Değeri

Eklenen sayfa.

### Ayrıca Bakınız

* sınıf [Page](../../page/)
* sınıf [PageCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Koleksiyondaki sayfaları belgeye ekler.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Yeni sayfaların başlangıç konumu. |
| pages | ICollection`1 | Sayfa koleksiyonu. |

### Ayrıca Bakınız

* sınıf [Page](../../page/)
* sınıf [PageCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Dizideki sayfaları belgeye ekler.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Yeni sayfaların başlangıç numarası. |
| pages | Page[] | Eklenmesi gereken sayfaların dizisi. |

### Ayrıca Bakınız

* sınıf [Page](../../page/)
* sınıf [PageCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)