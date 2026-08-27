---
title: "FormEditor.ExportItems"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 속성. 내보내기 값을 가진 콤보 박스 옵션을 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

내보내기 값을 가진 콤보 박스 옵션을 설정합니다.

```csharp
public string[][] ExportItems { get; set; }
```

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


