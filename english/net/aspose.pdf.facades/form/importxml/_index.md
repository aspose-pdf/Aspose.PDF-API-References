---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports the content of the fields from the xml file and put them into the new pdf
type: docs
weight: 310
url: /net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream, bool) {#importxml_1}

Imports the content of the fields from the xml file and put them into the new pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | The input xml stream. |
| IgnoreFormTemplateChanges | Boolean | If this parameter is true then all changes of the XFA form template will not be saved |

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream) {#importxml}

Imports the content of the fields from the xml file and put them into the new pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | Stream from which XML for import is read. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


