---
title: "FormEditor.Items"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 속성. 새로 생성된 리스트 박스 또는 콤보 박스에 추가될 항목을 설정합니다"
type: docs
weight: 50
url: /ko/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

새로 생성된 리스트 박스 또는 콤보 박스에 추가될 항목을 설정합니다.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


