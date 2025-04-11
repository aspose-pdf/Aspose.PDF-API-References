---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Überprüfen Sie, ob das Formular bereits das angegebene Feld hat
type: docs
weight: 280
url: /de/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Überprüfen Sie, ob das Formular bereits das angegebene Feld hat.

```csharp
public bool HasField(Field field)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| field | Field | Zu überprüfendes Feld. |

### Rückgabewert

`true`, wenn der angegebene Feldname zum Formular hinzugefügt wurde; andernfalls `false`.

### Siehe auch

* Klasse [Field](../../field/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) oder [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) des Feldes. |

### Rückgabewert

`true`, wenn der angegebene Feldname zum Formular hinzugefügt wurde; andernfalls `false`.

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde, mit der Möglichkeit, in die Kinderhierarchie der Felder zu suchen.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) oder [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) des Feldes. |
| searchChildren | Boolean | Wenn auf `true` gesetzt, wird die gesamte Hierarchie der Formularfelder nach dem angeforderten *fieldName* durchsucht (beachten Sie, dass in diesem Fall der [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) des erforderlichen Feldes als *fieldName* übergeben werden sollte). |

### Rückgabewert

`true`, wenn der angegebene Feldname zum Formular hinzugefügt wurde; andernfalls `false`.

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)