---
title: "Form.HasField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form metod. Kontrollerar om formuläret redan har det angivna fältet"
type: docs
weight: 300
url: /sv/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Kontrollera om formuläret redan har det angivna fältet.

```csharp
public bool HasField(Field field)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fält | Fält | Fält att kontrollera. |

### Returvärde

`true` om det angivna fältnamnet har lagts till i Form; annars, `false`.

### Se även

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Bestämmer om fältet med angivet namn redan har lagts till i formuläret.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) eller [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) för fältet. |

### Returvärde

`true` om det angivna fältnamnet har lagts till i Form; annars, `false`.

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Bestämmer om fältet med angivet namn redan har lagts till i formuläret, med möjlighet att titta i fältens underordnade hierarki.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) eller [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) för fältet. |
| searchChildren | Boolean | När den är satt till `true` kommer hela hierarkin av formulärfält att sökas efter det begärda *fieldName* (observera att i detta fall [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) för det erforderliga fältet ska skickas som *fieldName*). |

### Returvärde

`true` om det angivna fältnamnet har lagts till i Form; annars, `false`.

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


