---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Propriedade Stamp. Obtém ou define o status de fundo. Se verdadeiro, o carimbo será colocado como fundo da página carimbada. Por padrão, é definido como falso.
type: docs
weight: 30
url: /pt/net/aspose.pdf.facades/stamp/isbackground/
---
## Propriedade Stamp.IsBackground

Obtém ou define o status de fundo. Se verdadeiro, o carimbo será colocado como fundo da página carimbada. Por padrão, é definido como falso.

```csharp
public bool IsBackground { get; set; }
```

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)