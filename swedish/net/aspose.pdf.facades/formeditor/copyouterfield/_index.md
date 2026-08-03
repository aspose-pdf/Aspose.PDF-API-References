---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med originalsidnummer och koordinater. Observera: Endast för AcroForm-fält, exklusive radioknappar."
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | String | Det ursprungliga fullständigt kvalificerade fältnamnet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//kopierar textfält från source.pdf till PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | String | Det ursprungliga fullständigt kvalificerade fältnamnet. |
| pageNum | Int32 | Sidnumret för det nya fältet. Om -1 kopieras det nya fältet till samma sida som det gamla fältet är placerat på. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Enda för AcroForm‑fält (exklusive radioknappar).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | String | Det ursprungliga fullständigt kvalificerade fältnamnet. |
| pageNum | Int32 | Sidnumret för det nya fältet. Om -1 kopieras det nya fältet till samma sida som det gamla fältet är placerat på. |
| abskissa | Single | Abskissan för det nya fältet. Om -1 kommer abskissan att vara lika med den ursprungliga. |
| ordinat | Single | Ordinaten för det nya fältet. Om -1 kommer ordinaten att vara lika med den ursprungliga. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


