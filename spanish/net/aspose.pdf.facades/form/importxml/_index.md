---
title: ImportXml
second_title: Referencia de API de Aspose.PDF para .NET
description: Importa el contenido de los campos del archivo xml y los pone en el nuevo pdf.
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream, bool) {#importxml_1}

Importa el contenido de los campos del archivo xml y los pone en el nuevo pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputXmlStream | Stream | El flujo xml de entrada. |
| IgnoreFormTemplateChanges | Boolean | Si este parámetro es verdadero, no se guardarán todos los cambios de la plantilla de formulario XFA. |

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## ImportXml(Stream) {#importxml}

Importa el contenido de los campos del archivo xml y los pone en el nuevo pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputXmlStream | Stream | Secuencia desde la que se lee XML para importar. |

### Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->