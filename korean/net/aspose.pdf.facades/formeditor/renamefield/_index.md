---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 필드의 이름을 변경합니다"
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

필드의 이름을 변경합니다.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드의 이전 이름. |
| newFieldName | String | 필드의 새 이름. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


