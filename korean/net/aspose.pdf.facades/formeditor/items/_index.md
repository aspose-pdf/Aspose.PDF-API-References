---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 새로 생성된 목록 상자 또는 콤보 상자에 추가될 항목을 설정합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items 속성

새로 생성된 목록 상자 또는 콤보 상자에 추가될 항목을 설정합니다.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)