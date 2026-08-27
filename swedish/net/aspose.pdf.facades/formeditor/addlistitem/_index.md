---
title: "FormEditor.AddListItem"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Lägger till ett nytt objekt i listrutan"
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Lägger till ett nytt objekt i listboxen.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fältet till vilket det nya objektet kommer att läggas till. |
| itemName | String | Namn på nytt objekt. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Lägg till ett nytt objekt med Export‑värde till det befintliga listboxfältet, endast för AcroForm combo box field.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fältet till vilket objekt kommer att läggas till. |
| exportName | String[] | En strängarray som betecknar ett nytt listobjekt med Exportvärde, d.v.s. (Objektetikett, Exportvärde). |

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


