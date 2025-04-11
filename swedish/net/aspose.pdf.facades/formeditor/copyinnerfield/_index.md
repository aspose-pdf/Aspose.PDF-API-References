---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att produceras som innehåller allt som källdokumentet har förutom det nyligen kopierade fältet
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nyligen kopierade fältet.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det gamla fullt kvalificerade fältnamnet. |
| newFieldName | String | Det nya fullt kvalificerade fältnamnet. Om null, kommer det att sättas som fieldName + "~". |
| pageNum | Int32 | Sidnumret för att hålla det nya fältet. Om -1, kommer det nya fältet att kopieras till samma sida som det gamla. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nyligen kopierade fältet.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det gamla fullt kvalificerade fältnamnet. |
| newFieldName | String | Det nya fullt kvalificerade fältnamnet. Om null, kommer det att sättas som fieldName + "~". |
| pageNum | Int32 | Sidnumret för att hålla det nya fältet. Om -1, kommer det nya fältet att kopieras till samma sida som det gamla. |
| abscissa | Single | Abscissan för det nya fältet. Om -1, kommer abscissan att vara lika med den ursprungliga. |
| ordinate | Single | Ordinaten för det nya fältet. Om -1, kommer ordinaten att vara lika med den ursprungliga. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)