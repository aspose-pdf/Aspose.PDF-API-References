---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med ursprungligt sidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp)
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med ursprungligt sidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | Sträng | Det ursprungliga fullt kvalificerade fältnamnet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och ursprungliga koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | Sträng | Det ursprungliga fullt kvalificerade fältnamnet. |
| pageNum | Int32 | Sidnumret för att hålla det nya fältet. Om -1, kommer det nya fältet att kopieras till samma sida som det gamla. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | Sträng | Det ursprungliga fullt kvalificerade fältnamnet. |
| pageNum | Int32 | Sidnumret för att hålla det nya fältet. Om -1, kommer det nya fältet att kopieras till samma sida som det gamla. |
| abscissa | Enkel | Abscissan för det nya fältet. Om -1, kommer abscissan att vara lika med den ursprungliga. |
| ordinate | Enkel | Ordinaten för det nya fältet. Om -1, kommer ordinaten att vara lika med den ursprungliga. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)