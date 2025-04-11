---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 필드의 이름을 변경합니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField 메서드

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)