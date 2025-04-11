---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. 지정된 북마크 제목에 따라 북마크 제목을 수정합니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks 메서드

지정된 북마크 제목에 따라 북마크 제목을 수정합니다.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sTitle | 문자열 | 원본 북마크 제목. |
| dTitle | 문자열 | 수정된 북마크 제목. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)