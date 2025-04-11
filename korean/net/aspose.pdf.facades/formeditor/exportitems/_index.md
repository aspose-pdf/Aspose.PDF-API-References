---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 내보낼 값이 있는 콤보 상자에 대한 옵션을 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems 속성

내보낼 값이 있는 콤보 상자에 대한 옵션을 설정합니다.

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)