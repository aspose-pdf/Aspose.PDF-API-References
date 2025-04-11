---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 기존 필드를 지정된 페이지 번호의 동일한 위치로 복사합니다. 새 문서가 생성되며, 이는 소스 문서가 가진 모든 것을 포함하지만 새로 복사된 필드는 제외됩니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

지정된 페이지 번호의 동일한 위치로 기존 필드를 복사합니다. 새 문서가 생성되며, 이는 소스 문서가 가진 모든 것을 포함하지만 새로 복사된 필드는 제외됩니다.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | 이전의 완전한 필드 이름. |
| newFieldName | String | 새 완전한 필드 이름. null인 경우 fieldName + "~"로 설정됩니다. |
| pageNum | Int32 | 새 필드를 포함할 페이지 번호. -1인 경우 새 필드는 이전 필드가 호스팅된 동일한 페이지로 복사됩니다. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

기존 필드를 페이지 번호와 좌표로 지정된 새 위치로 복사합니다. 새 문서가 생성되며, 이는 소스 문서가 가진 모든 것을 포함하지만 새로 복사된 필드는 제외됩니다.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | 이전의 완전한 필드 이름. |
| newFieldName | String | 새 완전한 필드 이름. null인 경우 fieldName + "~"로 설정됩니다. |
| pageNum | Int32 | 새 필드를 포함할 페이지 번호. -1인 경우 새 필드는 이전 필드가 호스팅된 동일한 페이지로 복사됩니다. |
| abscissa | Single | 새 필드의 x좌표. -1인 경우 x좌표는 원래 값과 같습니다. |
| ordinate | Single | 새 필드의 y좌표. -1인 경우 y좌표는 원래 값과 같습니다. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)