---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Fügt ein neues Element zur Listenbox hinzu
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Fügt ein neues Element zur Listenbox hinzu.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, zu dem das neue Element hinzugefügt wird. |
| itemName | String | Name des neuen Elements. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Fügt ein neues Element mit Exportwert zum vorhandenen Listenfeld hinzu, nur für AcroForm-Kombinationsfeld.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, zu dem die Elemente hinzugefügt werden. |
| exportName | String[] | Ein String-Array, das ein neues Listenitem mit Exportwert angibt, d.h. (Elementbezeichnung, Exportwert). |

## Beispiele

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)