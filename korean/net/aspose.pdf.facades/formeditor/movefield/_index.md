---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 필드의 새로운 위치 설정
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField 메서드

필드의 새로운 위치를 설정합니다.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 이동해야 하는 필드의 이름. |
| llx | 단일 | 필드의 왼쪽 아래 모서리의 x좌표. |
| lly | 단일 | 필드의 왼쪽 아래 모서리의 y좌표. |
| urx | 단일 | 필드의 오른쪽 위 모서리의 x좌표. |
| ury | 단일 | 필드의 오른쪽 위 모서리의 y좌표. |

### 반환 값

필드 위치가 성공적으로 변경되면 true를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)