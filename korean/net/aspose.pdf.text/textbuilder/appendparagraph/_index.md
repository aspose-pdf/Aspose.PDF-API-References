---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder 메서드. Pdf 페이지에 텍스트 단락을 추가합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph 메서드

Pdf 페이지에 텍스트 단락을 추가합니다.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textParagraph | TextParagraph | 텍스트 단락 객체입니다. |

## 예제

이 예제는 텍스트 단락 객체를 생성하고 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### 참조

* 클래스 [TextParagraph](../../textparagraph/)
* 클래스 [TextBuilder](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)