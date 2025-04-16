---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 메서드. 원점을 （0, 0）에서 지정된 점으로 이동합니다. 원점은 왼쪽 하단이며 단위는 포인트（1인치 = 72포인트）입니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition 메서드

원점을 (0, 0)에서 지정된 점으로 이동합니다. 원점은 왼쪽 하단이며 단위는 포인트(1인치 = 72포인트)입니다.

```csharp
public void MovePosition(float moveX, float moveY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| moveX | Single | X 좌표. |
| moveY | Single | Y 좌표. |

## 예제

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### 참조

* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)