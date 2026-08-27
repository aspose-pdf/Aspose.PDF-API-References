---
title: "FontCollection 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.FontCollection 클래스. 글꼴 컬렉션을 나타냅니다."
type: docs
weight: 10710
url: /ko/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

글꼴 컬렉션을 나타냅니다.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | 컬렉션에 실제로 포함된 [`Font`](../font/) 객체 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다 |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 지정된 인덱스에 있는 글꼴 요소를 가져옵니다. (2개의 인덱서) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | 새 글꼴을 글꼴 리소스에 추가하고 자동으로 할당된 글꼴 리소스 이름을 반환합니다. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | 글꼴 컬렉션에 해당 글꼴이 존재하는지 확인합니다. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 전체 컬렉션을 호환 가능한 1차원 배열에 복사합니다. 대상 배열의 지정된 인덱스부터 시작합니다. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | 전체 컬렉션에 대한 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | 컬렉션에서 지정된 항목을 삭제합니다. |

## 비고

`FontCollection` 클래스로 표현된 글꼴 컬렉션은 여러 시나리오에서 사용됩니다. 예를 들어, [`Fonts`](../../aspose.pdf/resources/fonts/) 속성이 있는 리소스에서 사용됩니다.

## 예제

예제는 페이지에 선언된 모든 글꼴을 임베드하도록 만드는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 페이지 리소스에 선언된 모든 글꼴이 임베드되도록 보장합니다.
// 양식 리소스에 선언된 글꼴은 페이지 리소스에서 접근할 수 없다는 점에 유의하십시오.
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 또 보기

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


