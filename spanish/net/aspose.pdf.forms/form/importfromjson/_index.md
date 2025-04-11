---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Importa los campos del formulario PDF desde el formato JSON proporcionado en el flujo
type: docs
weight: 290
url: /es/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importa los campos del formulario PDF desde el formato JSON proporcionado en el flujo.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el cual leer la entrada JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de importación para cada campo del formulario.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Ver También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importa los campos del formulario PDF desde el formato JSON proporcionado en el archivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El nombre del archivo desde el cual leer la entrada JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de importación para cada campo del formulario.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Ver También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)