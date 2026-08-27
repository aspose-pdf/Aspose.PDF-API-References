---
title: "FormEditor.CopyInnerField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas som innehåller allt som källdokumentet har förutom det nykopierade fältet"
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det gamla fullständigt kvalificerade fältnamnet. |
| newFieldName | String | Det nya fullständigt kvalificerade fältnamnet. Om null kommer det att sättas till fieldName + "~". |
| pageNum | Int32 | Sidnumret för det nya fältet. Om -1 kopieras det nya fältet till samma sida som det gamla fältet är placerat på. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Skapar en kopia av textfältet på andra sidan.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det gamla fullständigt kvalificerade fältnamnet. |
| newFieldName | String | Det nya fullständigt kvalificerade fältnamnet. Om null kommer det att sättas till fieldName + "~". |
| pageNum | Int32 | Sidnumret för det nya fältet. Om -1 kopieras det nya fältet till samma sida som det gamla fältet är placerat på. |
| abskissa | Single | Abskissan för det nya fältet. Om -1 kommer abskissan att vara lika med den ursprungliga. |
| ordinat | Single | Ordinaten för det nya fältet. Om -1 kommer ordinaten att vara lika med den ursprungliga. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Skapar en kopia av textfältet på andra sidan.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


