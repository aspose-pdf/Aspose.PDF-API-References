---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Defina nova posição do campo
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/formeditor/movefield/
---
## Método FormEditor.MoveField

Defina nova posição do campo.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo que deve ser movido. |
| llx | Single | Abscissa do canto inferior esquerdo do campo. |
| lly | Single | Ordenada do canto inferior esquerdo do campo. |
| urx | Single | Abscissa do canto superior direito do campo. |
| ury | Single | Ordenada do canto superior direito do campo. |

### Valor de Retorno

true se a posição do campo foi alterada com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)