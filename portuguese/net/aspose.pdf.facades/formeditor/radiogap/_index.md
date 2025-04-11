---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Propriedade FormEditor. O membro para registrar o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/formeditor/radiogap/
---
## Propriedade FormEditor.RadioGap

O membro para registrar o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50.

```csharp
public float RadioGap { get; set; }
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