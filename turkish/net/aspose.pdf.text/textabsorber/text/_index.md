---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber özelliği. TextAbsorber'ın PDF belgesi veya sayfasında çıkardığı metni alır
type: docs
weight: 50
url: /tr/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text özelliği

[`TextAbsorber`](../) tarafından PDF belgesi veya sayfasında çıkarılan metni alır.

```csharp
public virtual string Text { get; }
```

## Örnekler

Örnek, PDF belgesinin tüm sayfalarından metin çıkarmanın nasıl yapılacağını gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Ayrıca Bakınız

* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)