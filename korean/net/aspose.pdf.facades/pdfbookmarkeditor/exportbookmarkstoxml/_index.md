---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfBookmarkEditor 메서드. 북마크를 XML 파일로 내보냅니다"
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
| xmlFile | String | 출력 XML 파일. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

북마크를 XML 스트림으로 내보냅니다.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 데이터가 저장될 출력 스트림. |

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


