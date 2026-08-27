---
title: "Field.ImportValueFromJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Fältmetod. Importerar data till de angivna fälten från en JSON-ström baserat på en exakt matchning av fältens fullständiga namn."
type: docs
weight: 210
url: /sv/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importerar data till de angivna fälten från en JSON‑ström, baserat på en exakt matchning av fältens fullständiga namn.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Inmatnings‑JSON‑ström som innehåller fältdata som ska importeras till fältet. |

### Returvärde

True om fältet hittades i JSON‑strömmen; annars - false

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Se även

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importerar data till det angivna fältet från en JSON‑ström, med hjälp av det fullständiga namn som anges i variabeln 'fieldFullNameInJSON' för matchning.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Inmatnings‑JSON‑ström som innehåller fältdata som ska importeras till fältet. |
| fieldFullNameInJSON | String | Namnet på data i JSON‑strömmen för matchning. Om data i JSON‑strömmen har en nästlad struktur bör det fullständiga namnet specificeras med alla föräldra‑ och barn‑element separerade med '.' |

### Returvärde

True om fältet hittades i json‑filen; annars - false

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Se även

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


