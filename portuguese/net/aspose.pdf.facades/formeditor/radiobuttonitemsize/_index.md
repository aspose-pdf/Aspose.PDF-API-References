---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do FormEditor. Obtém ou define o tamanho do item do botão de opção quando um novo campo de botão de opção é adicionado
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Propriedade FormEditor.RadioButtonItemSize

Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)