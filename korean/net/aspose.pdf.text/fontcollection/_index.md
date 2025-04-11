---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection 클래스. 글꼴 컬렉션을 나타냅니다.
type: docs
weight: 10530
url: /ko/net/aspose.pdf.text/fontcollection/
---
## FontCollection 클래스

글꼴 컬렉션을 나타냅니다.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | 컬렉션에 실제로 포함된 [`Font`](../font/) 객체 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | 컬렉션에 대한 접근이 동기화되었는지(스레드 안전) 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 지정된 인덱스의 글꼴 요소를 가져옵니다. (2개의 인덱서) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | 글꼴 리소스에 새 글꼴을 추가하고 자동으로 할당된 글꼴 리소스 이름을 반환합니다. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | 컬렉션에 특정 값이 포함되어 있는지 여부를 결정합니다. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | 글꼴 컬렉션에 글꼴이 존재하는지 확인합니다. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 지정된 인덱스에서 시작하여 호환되는 1차원 배열에 전체 컬렉션을 복사합니다. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | 전체 컬렉션에 대한 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | 컬렉션에서 지정된 항목을 삭제합니다. |

## 비고

`FontCollection` 클래스에 의해 나타나는 글꼴 컬렉션은 여러 시나리오에서 사용됩니다. 예를 들어, [`Fonts`](../../aspose.pdf/resources/fonts/) 속성이 있는 리소스에서 사용됩니다.

## 예제

이 예제는 페이지에 선언된 모든 글꼴을 포함된 글꼴로 만드는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 참조

* 클래스 [Font](../font/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)