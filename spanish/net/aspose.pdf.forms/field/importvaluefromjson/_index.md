---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Método de campo. Importa datos en los campos especificados desde un flujo JSON basado en una coincidencia exacta de los nombres completos de los campos
type: docs
weight: 210
url: /es/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importa datos en los campos especificados desde un flujo JSON, basado en una coincidencia exacta de los nombres completos de los campos.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputJsonStream | Stream | El flujo JSON de entrada que contiene los datos del campo que se van a importar en el campo. |

### Valor de Retorno

Verdadero si el campo fue encontrado en el flujo JSON; de lo contrario, falso

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Ver También

* clase [Field](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importa datos en el campo especificado desde un flujo JSON, utilizando el nombre completo especificado en la variable 'fieldFullNameInJSON' para la coincidencia.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputJsonStream | Stream | El flujo JSON de entrada que contiene los datos del campo que se van a importar en el campo. |
| fieldFullNameInJSON | String | El nombre de los datos dentro del flujo JSON para la coincidencia. Si los datos dentro del flujo JSON tienen una estructura anidada, el nombre completo debe especificarse con todos los elementos padre e hijo separados por '.' |

### Valor de Retorno

Verdadero si el campo fue encontrado en el archivo JSON; de lo contrario, falso

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Ver También

* clase [Field](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)