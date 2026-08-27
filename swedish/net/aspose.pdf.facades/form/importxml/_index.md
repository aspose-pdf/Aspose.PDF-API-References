---
title: "Form.ImportXml"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Importerar innehållet i fälten från xml-filen och placerar dem i den nya pdf-filen"
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Ström som XML för import läses från. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXmlStream | Stream | Den inmatade xml-strömmen. |
| IgnoreFormTemplateChanges | Boolean | Om den här parametern är sann kommer inga ändringar av XFA-formulärmall att sparas |

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


