---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: Propriedade FormEditor. A flag para indicar se os rádios estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## Propriedade FormEditor.RadioHoriz

A flag para indicar se os rádios estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro.

```csharp
public bool RadioHoriz { get; set; }
```

## Exemplos

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)