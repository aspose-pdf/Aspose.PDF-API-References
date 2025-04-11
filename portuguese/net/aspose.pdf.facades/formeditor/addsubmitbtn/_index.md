---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Adicionar botão de envio no formulário
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## Método FormEditor.AddSubmitBtn

Adicionar botão de envio no formulário.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do novo botão. |
| page | Int32 | Página onde o botão será colocado. |
| label | String | Legenda do botão. |
| url | String | URL do botão de envio. |
| llx | Single | Abscissa do canto inferior esquerdo. |
| lly | Single | Ordenada do canto inferior esquerdo. |
| urx | Single | Abscissa do canto superior direito. |
| ury | Single | Ordenada do canto superior direito. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)