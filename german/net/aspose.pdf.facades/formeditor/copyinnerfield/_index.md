---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Kopiert ein vorhandenes Feld an die gleiche Position auf der angegebenen Seitenzahl. Ein neues Dokument wird erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld.
type: docs
weight: 150
url: /de/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Kopiert ein vorhandenes Feld an die gleiche Position auf der angegebenen Seitenzahl. Ein neues Dokument wird erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der alte vollqualifizierte Feldname. |
| newFieldName | String | Der neue vollqualifizierte Feldname. Wenn null, wird er als fieldName + "~" gesetzt. |
| pageNum | Int32 | Die Seitenzahl, die das neue Feld halten soll. Wenn -1, wird das neue Feld auf die gleiche Seite kopiert wie das alte. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitenzahl als auch durch die Koordinaten angegeben ist. Ein neues Dokument wird erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der alte vollqualifizierte Feldname. |
| newFieldName | String | Der neue vollqualifizierte Feldname. Wenn null, wird er als fieldName + "~" gesetzt. |
| pageNum | Int32 | Die Seitenzahl, die das neue Feld halten soll. Wenn -1, wird das neue Feld auf die gleiche Seite kopiert wie das alte. |
| abscissa | Single | Die Abszisse des neuen Feldes. Wenn -1, wird die Abszisse gleich der ursprünglichen. |
| ordinate | Single | Die Ordinate des neuen Feldes. Wenn -1, wird die Ordinate gleich der ursprünglichen. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)