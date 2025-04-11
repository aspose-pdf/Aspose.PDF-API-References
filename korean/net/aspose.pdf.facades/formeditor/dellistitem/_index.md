---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 목록 필드에서 항목 삭제
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem 메서드

목록 필드에서 항목을 삭제합니다.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 필드의 이름. |
| itemName | 문자열 | 삭제해야 하는 항목의 이름. |

## 예제

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)