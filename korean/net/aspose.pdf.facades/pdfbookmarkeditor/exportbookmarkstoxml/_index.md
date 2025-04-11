---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. 북마크를 XML 파일로 내보냅니다
type: docs
weight: 50
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

북마크를 XML 파일로 내보냅니다.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlFile | 문자열 | 출력 XML 파일. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### 참조

* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

북마크를 XML 스트림으로 내보냅니다.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | 스트림 | 데이터가 저장될 출력 스트림. |

### 참조

* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)