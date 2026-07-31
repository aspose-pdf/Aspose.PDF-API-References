---
title: "Form.ImportXml"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf."
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXmlStream | Stream | Flusso da cui viene letto l'XML per l'importazione. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXmlStream | Stream | Il flusso xml di input. |
| IgnoreFormTemplateChanges | Boolean | Se questo parametro è true, tutte le modifiche del modello di modulo XFA non verranno salvate. |

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


