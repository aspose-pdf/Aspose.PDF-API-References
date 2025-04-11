---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 필드의 속성을 설정합니다.
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute 메서드

필드의 속성을 설정합니다.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 속성을 설정해야 하는 필드의 이름입니다. |
| flag | PropertyFlag | 플래그 (NoExport/ReadOnly/Required) |

### 반환 값

속성이 성공적으로 설정되면 true입니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### 참조

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)