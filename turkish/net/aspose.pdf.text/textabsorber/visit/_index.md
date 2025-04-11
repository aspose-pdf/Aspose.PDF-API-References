---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber metodu. Belirtilen sayfadaki metni çıkarır
type: docs
weight: 70
url: /tr/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Belirtilen sayfadaki metni çıkarır

```csharp
public virtual void Visit(Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | Pdf belge sayfa nesnesi. |

## Örnekler

Örnek, ilk PDF belge sayfasındaki metni nasıl çıkaracağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Belirtilen XForm'daki metni çıkarır.

```csharp
public virtual void Visit(XForm form)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| form | XForm | Pdf form nesnesi. |

## Örnekler

Örnek, ilk PDF belge sayfasındaki metni nasıl çıkaracağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### Ayrıca Bakınız

* sınıf [XForm](../../../aspose.pdf/xform/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Belirtilen belgede metni çıkarır

```csharp
public virtual void Visit(Document pdf)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdf | Document | Pdf belge nesnesi. |

## Örnekler

Örnek, PDF belgesindeki metni nasıl çıkaracağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)