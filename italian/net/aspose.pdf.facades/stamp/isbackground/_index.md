---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Stamp. Ottiene o imposta lo stato di sfondo. Se vero, il timbro sarà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su falso.
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/stamp/isbackground/
---
## Proprietà Stamp.IsBackground

Ottiene o imposta lo stato di sfondo. Se vero, il timbro sarà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su falso.

```csharp
public bool IsBackground { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi Anche

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)