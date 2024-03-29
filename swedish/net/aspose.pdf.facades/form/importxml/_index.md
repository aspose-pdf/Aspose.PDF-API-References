---
title: ImportXml
second_title: Aspose.PDF för .NET API Referens
description: Importerar innehållet i fälten från xml-filen och lägger in dem i den nya pdf-filen.
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream, bool) {#importxml_1}

Importerar innehållet i fälten från xml-filen och lägger in dem i den nya pdf-filen.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Ingångs-xml-strömmen. |
| IgnoreFormTemplateChanges | Boolean | Om denna parameter är sann kommer inte alla ändringar av XFA-formulärmallen att sparas |

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

---

## ImportXml(Stream) {#importxml}

Importerar innehållet i fälten från xml-filen och lägger in dem i den nya pdf-filen.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Stream från vilken XML för import läses. |

### Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
