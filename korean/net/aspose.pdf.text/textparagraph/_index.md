---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph 클래스. 여러 줄 텍스트 객체로서 텍스트 단락을 나타냅니다.
type: docs
weight: 10990
url: /ko/net/aspose.pdf.text/textparagraph/
---
## TextParagraph 클래스

여러 줄 텍스트 객체로서 텍스트 단락을 나타냅니다.

```csharp
public sealed class TextParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextParagraph](textparagraph/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | 후속 줄 들여쓰기 값을 가져오거나 설정합니다. 0이 아닌 값으로 설정하면 FormattingOptions.SubsequentLinesIndent 값보다 유리합니다. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | 서식 옵션을 가져오거나 설정합니다. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | 단락의 [`Rectangle`](./rectangle/) 내 텍스트의 수평 정렬을 가져오거나 설정합니다. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | 텍스트가 정렬되는지 여부를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | 패딩을 가져오거나 설정합니다. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | 단락의 위치를 가져오거나 설정합니다. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | 단락의 사각형을 가져오거나 설정합니다. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | 회전 각도를 도 단위로 가져오거나 설정합니다. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | 후속 줄 들여쓰기 값을 가져오거나 설정합니다. 0이 아닌 값으로 설정하면 FormattingOptions.SubsequentLinesIndent 값보다 유리합니다. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | 단락에 배치된 텍스트의 사각형을 가져옵니다. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | 단락의 [`Rectangle`](./rectangle/) 내 텍스트의 수직 정렬을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | 텍스트 상태 매개변수와 함께 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | 텍스트 상태 매개변수와 함께 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | 텍스트 상태 매개변수와 함께 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | 텍스트 상태 매개변수와 함께 텍스트 줄을 추가합니다. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | 텍스트 상태 매개변수와 함께 텍스트 줄을 추가합니다. |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | TextParagraph의 편집을 시작합니다. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | TextParagraph의 편집을 종료합니다. |

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

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)