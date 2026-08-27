---
title: "FormEditor.SetFieldAttribute"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 필드의 속성을 설정합니다."
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

필드의 속성을 설정합니다.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 속성을 설정해야 할 필드의 이름입니다. |
| 플래그 | PropertyFlag | 플래그 (NoExport/ReadOnly/Required) |

### 반환 값

속성이 성공적으로 설정된 경우 true.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### 또 보기

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


