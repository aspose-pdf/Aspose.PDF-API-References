---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection 클래스. CharInfo 객체 컬렉션을 나타냅니다.
type: docs
weight: 10450
url: /ko/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

CharInfo 객체 컬렉션을 나타냅니다.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | 컬렉션에 실제로 포함된 [`CharInfo`](../charinfo/) 객체 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | 컬렉션에 대한 접근이 동기화되어 있는지(스레드 안전) 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 지정된 인덱스에 있는 CharInfo 요소를 가져옵니다. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | 컬렉션이 읽기 전용이므로 NotImplementedException을 발생시킵니다. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | 컬렉션이 읽기 전용입니다. 항상 NotImplementedException을 발생시킵니다. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | 컬렉션에 특정 값이 포함되어 있는지 여부를 결정합니다. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 지정된 인덱스에서 시작하여 호환되는 1차원 배열에 전체 컬렉션을 복사합니다. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | 전체 컬렉션에 대한 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | 컬렉션이 읽기 전용이므로 NotImplementedException을 발생시킵니다. |

## Remarks

텍스트 세그먼트 문자에 대한 위치 정보를 제공합니다.

## Examples

예제는 모든 문자를 반복하고 문자를 검색하는 방법을 보여줍니다.

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### See Also

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)