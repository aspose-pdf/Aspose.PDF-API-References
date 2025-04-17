---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Importerar innehållet i fälten från xml-filen och lägger dem i den nya pdfen
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importerar innehållet i fälten från xml-filen och lägger dem i den nya pdf:en.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Stream från vilken XML för import läses. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importerar innehållet i fälten från xml-filen och lägger dem i den nya pdf:en.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Inmatnings-xml-streamen. |
| IgnoreFormTemplateChanges | Boolean | Om denna parameter är sann kommer alla ändringar av XFA-formmallen inte att sparas |

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)