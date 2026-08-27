---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 지정된 동작으로 북마크를 생성합니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

지정된 작업이 있는 북마크를 생성합니다.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 제목 | String | 북마크의 제목. |
| color | Color | 북마크 제목의 색상. |
| boldFlag | Boolean | 굵게 속성의 플래그. |
| italicFlag | Boolean | 이탤릭 속성의 플래그. |
| 파일 | String | 동작 유형이 "GoToR" 또는 "Launch"인 경우 필요한 다른 파일이나 애플리케이션. |
| actionType | String | 동작 유형. 값은 다음 중 하나일 수 있습니다: "GoToR", "Launch", "GoTo", "URI". |
| 대상 | String | 로컬 대상, 원격 대상 또는 URL. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


