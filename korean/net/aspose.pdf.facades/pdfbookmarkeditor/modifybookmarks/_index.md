---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfBookmarkEditor 메서드. 지정된 북마크 제목에 따라 북마크 제목을 수정합니다"
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

지정된 북마크 제목에 따라 북마크 제목을 수정합니다.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sTitle | String | 원본 북마크 제목. |
| dTitle | String | 수정된 북마크 제목. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


