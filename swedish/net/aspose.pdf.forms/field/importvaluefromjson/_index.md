---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Fältmetod. Importerar data till de angivna fälten från en JSON-ström baserat på en exakt matchning av fältens fullständiga namn
type: docs
weight: 210
url: /sv/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importerar data till de angivna fälten från en JSON-ström, baserat på en exakt matchning av fältens fullständiga namn.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Den inmatade JSON-strömmen som innehåller fältdata som ska importeras till fältet. |

### Returvärde

Sant om fältet hittades i JSON-strömmen; annars - falskt

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Se Även

* klass [Field](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* samling [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importerar data till det angivna fältet från en JSON-ström, med hjälp av det fullständiga namnet som anges i variabeln 'fieldFullNameInJSON' för matchning.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Den inmatade JSON-strömmen som innehåller fältdata som ska importeras till fältet. |
| fieldFullNameInJSON | String | Namnet på datan inom JSON-strömmen för matchning. Om datan inom JSON-strömmen har en nästlad struktur, bör det fullständiga namnet anges med alla föräldra- och barnobjekt separerade med '.' |

### Returvärde

Sant om fältet hittades i JSON-filen; annars - falskt

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Se Även

* klass [Field](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* samling [Aspose.PDF](../../../)