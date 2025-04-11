---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor metodu. Grafik elemanlarından bir dizeye svg resmi çıkarır, absorber ile bir predikat filtresi temsil eder
type: docs
weight: 20
url: /tr/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Grafik elemanlarından bir dizeye svg resmi çıkarır, !:absorber ile bir predikat filtresi temsil eder.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Grafik elemanlarını içeren GraphicsAbsorber nesnesi. |
| filter | Predicate`1 | Grafik elemanlarını filtrelemek için kullanılan bir predikat fonksiyonu. |
| page | Page | Absorber'ın grafik elemanlarını aldığı sayfa. |

### Dönüş Değeri

SVG içeriği ile dize.

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [GraphicsAbsorber](../../graphicsabsorber/)
* sınıf [GraphicElement](../../graphicelement/)
* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Grafik elemanlarından bir dosyaya svg resmi çıkarır, !:absorber ile bir predikat filtresi temsil eder.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Grafik elemanlarını içeren GraphicsAbsorber nesnesi. |
| filter | Predicate`1 | Grafik elemanlarını filtrelemek için kullanılan bir predikat fonksiyonu. |
| page | Page | Absorber'ın grafik elemanlarını aldığı sayfa. |
| svgFilePath | String | Hedef SVG dosya yolu. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [GraphicsAbsorber](../../graphicsabsorber/)
* sınıf [GraphicElement](../../graphicelement/)
* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Grafik elemanlarını bir SVG dizesine çıkarır. Seçenekler göz ardı edilir - gruplama, dikdörtgenden çıkarma

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elements | IEnumerable`1 | Dönüştürülecek grafik elemanları. |
| page | Page | Absorber'ın grafik elemanlarını aldığı sayfa. |

### Dönüş Değeri

SVG içeriği ile dize.

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [GraphicElement](../../graphicelement/)
* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Grafik elemanlarını tek bir SVG dosyasına çıkarır. Seçenekler göz ardı edilir - gruplama, dikdörtgenden çıkarma

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elements | IEnumerable`1 | Dönüştürülecek grafik elemanları. |
| page | Page | Absorber'ın grafik elemanlarını aldığı sayfa. |
| svgFilePath | String | Hedef SVG dosya yolu. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [GraphicElement](../../graphicelement/)
* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Bir sayfadan dizeye Svg resimleri çıkarır.

```csharp
public List<string> Extract(Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | Çıkarılacak sayfa. |

### Dönüş Değeri

SVG içerik dizeleri listesi.

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Bir sayfadan dosyalara Svg resimleri çıkarır.

```csharp
public void Extract(Page page, string directory)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | Çıkarılacak sayfa. |
| directory | String | SVG resimlerini yerleştirmek için hedef dizin. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG'ye dönüştürme sırasında bir hata oluşursa. |

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [SvgExtractor](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)