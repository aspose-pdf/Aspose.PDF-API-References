---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputXmlStream | Stream | Flujo desde el cual se lee el XML para importar. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputXmlStream | Stream | El flujo xml de entrada. |
| IgnoreFormTemplateChanges | Boolean | Si este parámetro es verdadero, entonces todos los cambios en la plantilla del formulario XFA no se guardarán |

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)