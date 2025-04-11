---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Importiert den Inhalt der Felder aus der XML-Datei und fügt sie in das neue PDF ein
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importiert den Inhalt der Felder aus der XML-Datei und fügt sie in das neue PDF ein.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputXmlStream | Stream | Stream, aus dem die XML für den Import gelesen wird. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importiert den Inhalt der Felder aus der XML-Datei und fügt sie in das neue PDF ein.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputXmlStream | Stream | Der Eingabe-XML-Stream. |
| IgnoreFormTemplateChanges | Boolean | Wenn dieser Parameter wahr ist, werden alle Änderungen des XFA-Formularvorlagen nicht gespeichert |

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)