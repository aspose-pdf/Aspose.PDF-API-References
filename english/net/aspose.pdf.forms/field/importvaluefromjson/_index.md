---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Field method. Imports data into the specified fields from a JSON stream based on an exact match of the fields full names
type: docs
weight: 210
url: /net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Imports data into the specified fields from a JSON stream, based on an exact match of the fields' full names.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | The input JSON stream containing the field data to be imported into the field. |

### Return Value

True if the field was found in JSON stream; otherwise - false

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### See Also

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Imports data into the specified field from a JSON stream, using the full name specified in the 'fieldFullNameInJSON' variable for matching.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | The input JSON stream containing the field data to be imported into the field. |
| fieldFullNameInJSON | String | The name of the data within the JSON stream for matching. If the data within the JSON stream has a nested structure, the full name should be specified with all parent and child items separated by '.' |

### Return Value

True if the field was found in json file; otherwise - false

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### See Also

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


