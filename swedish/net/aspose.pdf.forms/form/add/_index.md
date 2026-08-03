---
title: "Form.Add"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Lägger till fält i formuläret."
type: docs
weight: 210
url: /sv/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Lägger till ett fält i formuläret.

```csharp
public void Add(Field field, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fält | Fält | Fält som måste läggas till. |
| pageNumber | Int32 | Sidindex där det tillagda fältet kommer att placeras. |

### Se även

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Lägger till ett fält i formuläret.

```csharp
public void Add(Field field)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fält | Fält | Fält som måste läggas till. |

### Se även

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Lägger till ett nytt fält i formuläret; om detta fält redan är placerat i ett annat eller i detta formulär skapas en kopia av fältet.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fält | Fält | Fältnamn. |
| partialName | String | Namn på fältet i formuläret. |
| pageNumber | Int32 | Sidnummer där fältet kommer att läggas till. |

### Returvärde

Tillagt fält returneras. Om en kopia av fältet skapades kommer den att returneras.

### Se även

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


