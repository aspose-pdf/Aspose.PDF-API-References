---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metodu. Değiştirilen belgeyi dosyaya kaydeder
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Değiştirilen belgeyi dosyaya kaydeder.

```csharp
public override void Save(string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Belgenin kaydedileceği dosyanın yolu. |

## Örnekler

Aşağıdaki örnek, değiştirilen PDF belgesinin nasıl kaydedileceğini göstermektedir.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Değiştirilen belgeyi akışa kaydeder.

```csharp
public override void Save(Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Değiştirilen PDF belgesinin kaydedileceği akış. |

## Örnekler

Aşağıdaki örnek, değiştirilen PDF belgesinin akışa nasıl kaydedileceğini göstermektedir.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)