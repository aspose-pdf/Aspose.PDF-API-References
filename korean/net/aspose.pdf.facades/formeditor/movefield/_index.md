---
title: "FormEditor.MoveField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 필드의 새 위치를 설정합니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

필드의 새 위치를 설정합니다.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이동해야 할 필드의 이름입니다. |
| llx | Single | 필드의 왼쪽 하단 모서리의 x좌표입니다. |
| lly | Single | 필드의 왼쪽 하단 모서리의 y좌표입니다. |
| urx | Single | 필드의 오른쪽 상단 모서리의 x좌표입니다. |
| ury | Single | 필드의 오른쪽 상단 모서리의 y좌표입니다. |

### 반환 값

필드 위치가 성공적으로 변경된 경우 true.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


