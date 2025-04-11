---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Form-metod. Kontrollera om formuläret redan har angivet fält
type: docs
weight: 280
url: /sv/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Kontrollera om formuläret redan har angivet fält.

```csharp
public bool HasField(Field field)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | Field | Fält att kontrollera. |

### Returvärde

`true` om det angivna fältnamnet har lagts till i formuläret; annars, `false`.

### Se Även

* klass [Field](../../field/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Bestämmer om fältet med angivet namn redan har lagts till i formuläret.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) eller [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) av fältet. |

### Returvärde

`true` om det angivna fältnamnet har lagts till i formuläret; annars, `false`.

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Bestämmer om fältet med angivet namn redan har lagts till i formuläret, med möjlighet att söka i barnhierarkin av fält.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) eller [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) av fältet. |
| searchChildren | Boolean | När den är inställd på `true` kommer hela hierarkin av formulärfält att sökas efter det begärda *fieldName* (notera att i detta fall bör [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) av det erforderliga fältet skickas som *fieldName*). |

### Returvärde

`true` om det angivna fältnamnet har lagts till i formuläret; annars, `false`.

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)