---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Copia um campo existente de um documento PDF para outro documento com o número da página original e as ordenadas. Nota: Apenas para campos AcroForm, excluindo caixa de rádio.
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia um campo existente de um documento PDF para outro documento com o número da página original e as ordenadas. Nota: Apenas para campos AcroForm (excluindo caixa de rádio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | O nome do documento PDF que contém o campo a ser copiado. |
| fieldName | String | O nome do campo totalmente qualificado original. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia um campo existente de um documento PDF para outro documento com o número da página especificado e as ordenadas originais. Nota: Apenas para campos AcroForm (excluindo caixa de rádio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | O nome do documento PDF que contém o campo a ser copiado. |
| fieldName | String | O nome do campo totalmente qualificado original. |
| pageNum | Int32 | O número da página para manter o novo campo. Se -1, o novo campo será copiado para a mesma página que o antigo. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia um campo existente de um documento PDF para outro documento com o número da página especificado e as ordenadas. Nota: Apenas para campos AcroForm (excluindo caixa de rádio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | O nome do documento PDF que contém o campo a ser copiado. |
| fieldName | String | O nome do campo totalmente qualificado original. |
| pageNum | Int32 | O número da página para manter o novo campo. Se -1, o novo campo será copiado para a mesma página que o antigo. |
| abscissa | Single | A abscissa do novo campo. Se -1, a abscissa será igual à original. |
| ordinate | Single | A ordenada do novo campo. Se -1, a ordenada será igual à original. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)