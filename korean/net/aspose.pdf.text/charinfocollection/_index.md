---
title: "클래스 CharInfoCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.CharInfoCollection 클래스. CharInfo 객체 컬렉션을 나타냅니다."
type: docs
weight: 10630
url: /ko/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

CharInfo 객체 컬렉션을 나타냅니다.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | 컬렉션에 실제로 포함된 [`CharInfo`](../charinfo/) 객체 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다 |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 지정된 인덱스에 있는 CharInfo 요소를 가져옵니다. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | 컬렉션은 읽기 전용이며, NotImplementedException을 발생시킵니다. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | 컬렉션은 읽기 전용입니다. 항상 NotImplementedException을 발생시킵니다. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 전체 컬렉션을 호환 가능한 1차원 배열에 복사합니다. 대상 배열의 지정된 인덱스부터 시작합니다. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | 전체 컬렉션에 대한 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | 컬렉션은 읽기 전용이며, NotImplementedException을 발생시킵니다. |

## 비고

텍스트 세그먼트 문자들의 위치 정보에 대한 접근을 제공합니다.

## 예제

예제는 모든 문자를 반복하고 문자를 검색하는 방법을 보여줍니다.

```csharp
//문서 열기
Document pdfDocument = new Document(inFile);
//페이지의 모든 텍스트 객체를 수집하기 위해 TextFragmentAbsorber 객체를 생성합니다
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//모든 페이지에 대해 흡수기를 적용합니다
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//추출된 텍스트 조각을 가져옵니다
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//조각들을 반복합니다
foreach (TextFragment textFragment in textFragmentCollection)
{
    //세그먼트를 순회합니다
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //문자를 순회합니다
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // 문자 위치와 사각형 정보를 출력합니다
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### 또 보기

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


