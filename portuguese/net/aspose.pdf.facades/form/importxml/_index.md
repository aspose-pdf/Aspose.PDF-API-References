---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf
type: docs
weight: 310
url: /pt/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputXmlStream | Stream | Stream do qual o XML para importação é lido. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputXmlStream | Stream | O stream xml de entrada. |
| IgnoreFormTemplateChanges | Boolean | Se este parâmetro for verdadeiro, todas as alterações do modelo de formulário XFA não serão salvas |

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)