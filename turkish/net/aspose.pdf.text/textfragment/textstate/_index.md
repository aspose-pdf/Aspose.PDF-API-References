---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment özelliği. TextFragment nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar
type: docs
weight: 150
url: /tr/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState özelliği

[`TextFragment`](../) nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar.

```csharp
public TextFragmentState TextState { get; }
```

## Açıklamalar

Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor

## Örnekler

Örnek, `TextState` nesnesi ile metin rengini ve font boyutunu nasıl değiştireceğini gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../../textfragmentabsorber/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextFragmentState](../../textfragmentstate/)
* sınıf [TextFragment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)