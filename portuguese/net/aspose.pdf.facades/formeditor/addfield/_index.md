---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Adicionar campo do tipo especificado ao formulário
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/formeditor/addfield/
---
## AdicionarCampo(FieldType, string, int, float, float, float, float) {#addfield}

Adicionar campo do tipo especificado ao formulário.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldType | FieldType | Tipo do campo que deve ser adicionado. |
| fieldName | String | Nome do campo que deve ser adicionado. |
| pageNum | Int32 | Número da página onde o novo campo deve ser colocado. |
| llx | Single | Abscissa do canto inferior esquerdo do campo. |
| lly | Single | Ordenada do canto inferior esquerdo do campo. |
| urx | Single | Abscissa do canto superior direito do campo. |
| ury | Single | Ordenada do canto superior direito do campo. |

### Valor de Retorno

true se o campo foi adicionado com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Veja Também

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AdicionarCampo(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Adicionar campo do tipo especificado ao formulário.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldType | FieldType | Tipo do campo que deve ser adicionado. |
| fieldName | String | Nome do campo que deve ser adicionado. |
| initValue | String | Valor inicial do campo. |
| pageNum | Int32 | Número da página onde o novo campo deve ser colocado. |
| llx | Single | Abscissa do canto inferior esquerdo do campo. |
| lly | Single | Ordenada do canto inferior esquerdo do campo. |
| urx | Single | Abscissa do canto superior direito do campo. |
| ury | Single | Ordenada do canto superior direito do campo. |

### Valor de Retorno

true se o campo foi adicionado com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Veja Também

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)