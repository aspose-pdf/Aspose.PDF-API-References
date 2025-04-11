---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Feldmethode. Importiert Daten in die angegebenen Felder aus einem JSON-Stream basierend auf einer genauen Übereinstimmung der vollständigen Feldnamen
type: docs
weight: 210
url: /de/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Feldnamen.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputJsonStream | Stream | Der Eingabe-JSON-Stream, der die Felddaten enthält, die in das Feld importiert werden sollen. |

### Rückgabewert

Wahr, wenn das Feld im JSON-Stream gefunden wurde; andernfalls - falsch

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Siehe auch

* Klasse [Field](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputJsonStream | Stream | Der Eingabe-JSON-Stream, der die Felddaten enthält, die in das Feld importiert werden sollen. |
| fieldFullNameInJSON | String | Der Name der Daten innerhalb des JSON-Streams zur Übereinstimmung. Wenn die Daten innerhalb des JSON-Streams eine verschachtelte Struktur haben, sollte der vollständige Name mit allen übergeordneten und untergeordneten Elementen, die durch '.' getrennt sind, angegeben werden. |

### Rückgabewert

Wahr, wenn das Feld in der JSON-Datei gefunden wurde; andernfalls - falsch

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Siehe auch

* Klasse [Field](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)