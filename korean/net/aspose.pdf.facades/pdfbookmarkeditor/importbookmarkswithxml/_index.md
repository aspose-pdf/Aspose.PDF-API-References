---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfBookmarkEditor 메서드. XML 파일에서 문서로 북마크를 가져옵니다"
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

XML 파일에서 문서로 북마크를 가져옵니다.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlFile | String | 북마크 목록을 포함하는 XML 파일. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

XML 파일에서 문서로 북마크를 가져옵니다.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 북마크 데이터가 포함된 스트림. |

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


