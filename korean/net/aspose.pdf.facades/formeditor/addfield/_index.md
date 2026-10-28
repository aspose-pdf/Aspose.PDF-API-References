---
title: "FormEditor.AddField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor method. 지정된 유형의 필드를 양식에 추가합니다."
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

지정된 유형의 필드를 양식에 추가합니다.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldType | FieldType | 추가해야 할 필드의 유형. |
| fieldName | String | 추가해야 할 필드의 이름. |
| pageNum | Int32 | 새 필드를 배치해야 하는 페이지 번호. |
| llx | Single | 필드의 왼쪽 하단 모서리의 x좌표입니다. |
| lly | Single | 필드의 왼쪽 아래 모서리의 좌표값. |
| urx | Single | 필드의 오른쪽 상단 모서리의 x좌표입니다. |
| ury | Single | 필드의 오른쪽 상단 모서리의 y좌표입니다. |

### 반환 값

필드가 성공적으로 추가된 경우 true.

## 예제

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### 또 보기

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

지정된 유형의 필드를 양식에 추가합니다.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldType | FieldType | 추가해야 할 필드의 유형. |
| fieldName | String | 추가해야 할 필드의 이름. |
| initValue | String | 필드의 초기값. |
| pageNum | Int32 | 새 필드를 배치해야 하는 페이지 번호. |
| llx | Single | 필드의 왼쪽 하단 모서리의 x좌표입니다. |
| lly | Single | 필드의 왼쪽 아래 모서리의 좌표값. |
| urx | Single | 필드의 오른쪽 상단 모서리의 x좌표입니다. |
| ury | Single | 필드의 오른쪽 상단 모서리의 y좌표입니다. |

### 반환 값

필드가 성공적으로 추가된 경우 true.

## 예제

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### 또 보기

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


