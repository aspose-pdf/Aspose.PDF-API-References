---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Copia um campo existente para a mesma posição no número da página especificada. Um novo documento será produzido, que contém tudo o que o documento de origem possui, exceto pelo campo copiado recentemente.
type: docs
weight: 150
url: /pt/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copia um campo existente para a mesma posição no número da página especificada. Um novo documento será produzido, que contém tudo o que o documento de origem possui, exceto pelo campo copiado recentemente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O antigo nome de campo totalmente qualificado. |
| newFieldName | String | O novo nome de campo totalmente qualificado. Se nulo, será definido como fieldName + "~". |
| pageNum | Int32 | O número da página para manter o novo campo. Se -1, o novo campo será copiado para a mesma página que o antigo. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Veja Também

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas ordenadas. Um novo documento será produzido, que contém tudo o que o documento de origem possui, exceto pelo campo copiado recentemente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O antigo nome de campo totalmente qualificado. |
| newFieldName | String | O novo nome de campo totalmente qualificado. Se nulo, será definido como fieldName + "~". |
| pageNum | Int32 | O número da página para manter o novo campo. Se -1, o novo campo será copiado para a mesma página que o antigo. |
| abscissa | Single | A abscissa do novo campo. Se -1, a abscissa será igual à original. |
| ordinate | Single | A ordenada do novo campo. Se -1, a ordenada será igual à original. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Veja Também

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)