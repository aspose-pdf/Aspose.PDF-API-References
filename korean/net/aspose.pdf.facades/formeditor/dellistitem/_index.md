---
title: "FormEditor.DelListItem"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 리스트 필드에서 항목을 삭제합니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

목록 필드에서 항목을 삭제합니다.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름. |
| itemName | String | 삭제해야 할 항목의 이름. |

## 예제

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


