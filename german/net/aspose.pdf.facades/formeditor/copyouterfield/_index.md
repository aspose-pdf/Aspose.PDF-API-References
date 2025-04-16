---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der ursprünglichen Seitenzahl und den Koordinaten. Hinweis: Nur für AcroForm-Felder.
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der ursprünglichen Seitenzahl und den Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Boxen).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name des PDF-Dokuments, das das zu kopierende Feld enthält. |
| fieldName | String | Der ursprüngliche vollständig qualifizierte Feldname. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der angegebenen Seitenzahl und den ursprünglichen Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Boxen).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name des PDF-Dokuments, das das zu kopierende Feld enthält. |
| fieldName | String | Der ursprüngliche vollständig qualifizierte Feldname. |
| pageNum | Int32 | Die Seitenzahl, die das neue Feld halten soll. Wenn -1, wird das neue Feld auf derselben Seite wie das alte platziert. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der angegebenen Seitenzahl und den Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Boxen).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name des PDF-Dokuments, das das zu kopierende Feld enthält. |
| fieldName | String | Der ursprüngliche vollständig qualifizierte Feldname. |
| pageNum | Int32 | Die Seitenzahl, die das neue Feld halten soll. Wenn -1, wird das neue Feld auf derselben Seite wie das alte platziert. |
| abscissa | Single | Die Abszisse des neuen Feldes. Wenn -1, wird die Abszisse der ursprünglichen gleichgesetzt. |
| ordinate | Single | Die Ordinate des neuen Feldes. Wenn -1, wird die Ordinate der ursprünglichen gleichgesetzt. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)