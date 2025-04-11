---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alanların içeriğini xml dosyasından alır ve yeni pdf'ye yerleştirir
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Alanların içeriğini xml dosyasından alır ve yeni pdf'ye yerleştirir.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputXmlStream | Stream | İçe aktarma için XML'in okunduğu akış. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Alanların içeriğini xml dosyasından alır ve yeni pdf'ye yerleştirir.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputXmlStream | Stream | Girdi xml akışı. |
| IgnoreFormTemplateChanges | Boolean | Bu parametre doğruysa, XFA form şablonundaki tüm değişiklikler kaydedilmeyecektir. |

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)