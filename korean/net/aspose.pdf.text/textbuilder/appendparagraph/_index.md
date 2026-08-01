---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextBuilder 메서드. 텍스트 단락을 Pdf 페이지에 추가합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

텍스트 단락을 PDF 페이지에 추가합니다.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textParagraph | TextParagraph | 텍스트 단락 객체. |

## 예제

예제에서는 텍스트 단락 객체를 생성하고 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// 텍스트 단락을 생성합니다
TextParagraph paragraph = new TextParagraph();
           
// 단락 사각형을 설정합니다
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// 단어 줄바꿈 옵션을 설정합니다
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// 문자열 라인을 추가합니다
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// TextBuilder를 사용하여 단락을 Pdf 페이지에 추가합니다
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// Pdf 문서를 저장합니다
doc.Save(outFile);
```

### 또 보기

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


