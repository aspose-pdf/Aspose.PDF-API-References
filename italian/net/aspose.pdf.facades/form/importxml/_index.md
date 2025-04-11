---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Metodo di formazione. Importa i contenuti dei campi dal file XML e mettili nel nuovo PDF.
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXmlStream | Stream | Stream da cui viene letto l'XML per l'importazione. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXmlStream | Stream | Lo stream xml di input. |
| IgnoreFormTemplateChanges | Boolean | Se questo parametro è vero, tutte le modifiche del modello di modulo XFA non verranno salvate |

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)