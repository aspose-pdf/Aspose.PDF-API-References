---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. XML 파일에서 문서로 북마크를 가져옵니다.
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
| xmlFile | 문자열 | 북마크 목록이 포함된 XML 파일입니다. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

XML 파일에서 문서로 북마크를 가져옵니다.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | 스트림 | 북마크 데이터가 포함된 스트림입니다. |

### 참조

* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)