---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: Proprietà FormEditor. Il flag per indicare se i radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## Proprietà FormEditor.RadioHoriz

Il flag per indicare se i radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true.

```csharp
public bool RadioHoriz { get; set; }
```

## Esempi

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)