---
title: "FormEditor.RadioButtonItemSize"
linktitle: "RadioButtonItemSize"
articleTitle: "RadioButtonItemSize"
second_title: "Aspose.PDF for .NET"
description: "Gets or sets size of radio button item size (when new radio button field is added). formEditor = new Aspose.Pdf.Facades.FormEditor(\"PdfForm.pdf\", \"FormEditor..."
type: docs
weight: 510
url: "/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/"
product_version: "26.9.0"
---
## FormEditor.RadioButtonItemSize property

Gets or sets size of radio button item size (when new radio button field is added). 
 
 formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.RadioGap = 4;
 formEditor.RadioHoriz = false;
 formEditor.RadioButtonItemSize = 20;
 formEditor.Items = new string[] { "First", "Second", "Third" };
 formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.Save();

```csharp
public double RadioButtonItemSize { get; set; }
```

### Property Value

double

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

