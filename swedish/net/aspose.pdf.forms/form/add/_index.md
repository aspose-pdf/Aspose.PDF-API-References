---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Lägger till fält på formuläret
type: docs
weight: 190
url: /sv/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Lägger till fält på formuläret.

```csharp
public void Add(Field field, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | Field | Fält som måste läggas till. |
| pageNumber | Int32 | Sidindex där det tillagda fältet kommer att placeras. |

### Se Även

* klass [Field](../../field/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Lägger till fält på formuläret.

```csharp
public void Add(Field field)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | Field | Fält som måste läggas till. |

### Se Även

* klass [Field](../../field/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Lägger till ett nytt fält till formuläret; Om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | Field | Fältnamn. |
| partialName | String | Namn på fältet på formuläret. |
| pageNumber | Int32 | Sidnummer där fältet kommer att läggas till. |

### Returvärde

Det tillagda fältet returneras. Om en kopia av fältet skapades kommer det att returneras.

### Se Även

* klass [Field](../../field/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../../)