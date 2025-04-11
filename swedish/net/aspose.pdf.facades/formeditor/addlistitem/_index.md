---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Lägger till nytt objekt i listboxen
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Lägger till nytt objekt i listboxen.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet där det nya objektet kommer att läggas till. |
| itemName | String | Namnet på det nya objektet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Lägg till ett nytt objekt med Export-värde till det befintliga listboxfältet, endast för AcroForm kombinationsruta fält.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet där objekten kommer att läggas till. |
| exportName | String[] | En strängarray som betecknar ett nytt listobjekt med Exportvärde, dvs. (Objektetikett, Exportvärde). |

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)