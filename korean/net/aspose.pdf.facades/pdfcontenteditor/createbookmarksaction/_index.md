---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 지정된 작업으로 북마크를 생성합니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction 메서드

지정된 작업으로 북마크를 생성합니다.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| title | String | 북마크의 제목. |
| color | Color | 북마크 제목의 색상. |
| boldFlag | Boolean | 굵게 표시할지 여부. |
| italicFlag | Boolean | 기울임꼴 표시할지 여부. |
| file | String | 작업 유형이 "GoToR" 또는 "Launch"일 때 필요한 다른 파일 또는 애플리케이션. |
| actionType | String | 작업 유형. 값은 "GoToR", "Launch", "GoTo", "URI"일 수 있습니다. |
| destination | String | 로컬 목적지 또는 원격 목적지 또는 URL. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)