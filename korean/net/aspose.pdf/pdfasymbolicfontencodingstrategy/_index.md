---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy 클래스. 이 클래스는 TrueType 심볼릭 글꼴에 하나 이상의 인코딩이 있을 경우 인코딩 데이터를 복사하는 과정을 조정하기 위해 사용할 수 있는 규칙을 설명합니다. PDF/A 형식으로 변환된 일부 PDF 문서는 "More than one encoding in symbolic TrueType font's cmap" 오류를 발생시킬 수 있습니다. 이 오류의 원인은 무엇일까요? 모든 TrueType 심볼릭 글꼴은 내부 데이터에 특별한 cmap 테이블을 가지고 있습니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑하며, 사용된 인코딩을 설명하는 여러 인코딩 하위 테이블을 포함할 수 있습니다. cmap 테이블에 대한 고급 정보는 https//developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html 을 참조하십시오. 보통 cmap 테이블에는 여러 인코딩 하위 테이블이 포함되지만, PDF/A 표준은 해당 글꼴에 대해 PDF/A 문서 내에 하나의 인코딩 하위 테이블만 남거나 글꼴 하위 테이블 중 （3,0） 인코딩 하위 테이블이 있어야 한다고 요구합니다. 그리고 여기서 핵심 질문은 다른 하위 테이블에서 어떤 데이터를 가져와 대상 인코딩 테이블 （3,0）에 복사해야 하는가 입니다. 대부분의 글꼴은 모든 인코딩 하위 테이블이 서로 완전히 일관된 'well-formed' cmap 테이블을 가지고 있습니다. 그러나 일부 글꼴은 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 하위 테이블에서는 유니코드 100에 대해 글리프 인덱스 100을 가지지만 다른 하위 테이블에서는 동일한 유니코드 100에 대해 글리프 인덱스 200을 가질 수 있습니다. 이 문제를 해결하기 위해 특별한 전략이 필요합니다. 기본적으로 사용되는 전략은 mac subtable（10）을 먼저 찾는 것입니다. 이 테이블이 발견되면 해당 데이터만을 사용하여 대상 테이블 （3,0）을 채웁니다. 만약 mac subtable이 발견되지 않으면, （3,0）을 제외한 모든 하위 테이블을 순회하면서 데이터를 대상 （3,0） 하위 테이블로 복사합니다. 또한, 대상 테이블에 해당 유니코드가 아직 존재하지 않을 경우에만 각 유니코드（및 글리프 인덱스）의 매핑이 복사됩니다. 예를 들어, 첫 번째 하위 테이블에서 유니코드 100의 글리프 인덱스가 100이고, 다음 하위 테이블에서 동일한 유니코드 100의 글리프 인덱스가 200인 경우, 첫 번째 하위 테이블의 데이터（유니코드 100, 글리프 인덱스 100）만 복사됩니다. 즉, 이전 하위 테이블의 데이터가 이후의 데이터보다 우선합니다.
type: docs
weight: 8330
url: /ko/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy 클래스

이 클래스는 TrueType 심볼릭 글꼴에 하나 이상의 인코딩이 있을 경우 인코딩 데이터를 복사하는 과정을 조정하기 위해 사용할 수 있는 규칙을 설명합니다. PDF/A 형식으로 변환된 일부 PDF 문서는 "More than one encoding in symbolic TrueType font's cmap" 오류를 발생시킬 수 있습니다. 이 오류의 원인은 무엇일까요? 모든 TrueType 심볼릭 글꼴은 내부 데이터에 특별한 "cmap" 테이블을 가지고 있습니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑하며, 사용된 인코딩을 설명하는 여러 인코딩 하위 테이블을 포함할 수 있습니다. cmap 테이블에 대한 고급 정보는 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html을 참조하십시오. 보통 cmap 테이블에는 여러 인코딩 하위 테이블이 포함되지만, PDF/A 표준은 해당 글꼴에 대해 PDF/A 문서 내에 하나의 인코딩 하위 테이블만 남거나 글꼴 하위 테이블 중 (3,0) 인코딩 하위 테이블이 있어야 한다고 요구합니다. 그리고 여기서 핵심 질문은 다른 하위 테이블에서 어떤 데이터를 가져와 대상 인코딩 테이블 (3,0)에 복사해야 하는가 입니다. 대부분의 글꼴은 모든 인코딩 하위 테이블이 서로 완전히 일관된 'well-formed' cmap 테이블을 가지고 있습니다. 그러나 일부 글꼴은 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 하위 테이블에서는 유니코드 100에 대해 글리프 인덱스 100을 가지지만 다른 하위 테이블에서는 동일한 유니코드 100에 대해 글리프 인덱스 200을 가질 수 있습니다. 이 문제를 해결하기 위해 특별한 전략이 필요합니다. 기본적으로 사용되는 전략은 다음과 같습니다: mac subtable(1,0)을 먼저 찾습니다. 이 테이블이 발견되면 해당 데이터만을 사용하여 대상 테이블 (3,0)을 채웁니다. 만약 mac subtable이 발견되지 않으면, (3,0)을 제외한 모든 하위 테이블을 순회하면서 데이터를 대상 (3,0) 하위 테이블로 복사합니다. 또한, 대상 테이블에 아직 해당 유니코드가 존재하지 않을 경우에만 각 유니코드(및 글리프 인덱스)의 매핑이 복사됩니다. 예를 들어, 첫 번째 하위 테이블에서 유니코드 100의 글리프 인덱스가 100이고, 다음 하위 테이블에서 동일한 유니코드 100의 글리프 인덱스가 200인 경우, 첫 번째 하위 테이블의 데이터(유니코드=100, 글리프 인덱스=100)만 복사됩니다. 즉, 이전 하위 테이블의 데이터가 이후의 데이터보다 우선합니다. 

이 클래스 `PdfASymbolicFontEncodingStrategy`의 속성은 기본 동작을 조정하는 데 도움을 줍니다. 만약 타입이 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)인 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 속성이 설정되면, 해당 하위 테이블이 기본적으로 사용되는 mac subtable(1,0)보다 우선적으로 사용됩니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)의 값 'MacTable'은 기본적으로 사용되는 mac subtable(1,0)을 가리키므로 이 경우 의미가 없습니다. 속성 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/)는 모든 하위 테이블에 대한 우선순위를 무시합니다. 만약 이 속성이 설정되면, 선언된 큐 내의 하위 테이블만 지정된 순서대로 사용됩니다. 만약 지정된 하위 테이블이 발견되지 않으면, 위에서 설명한 기본 순회 및 복사 전략이 사용됩니다. 객체 [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/)은 사용되는 인코딩 하위 테이블을 지정합니다. 이 하위 테이블은 멤버(PlatformID, PlatformSpecificId)의 조합이나 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 열거형을 통해 설정할 수 있습니다. 글꼴에 (3,0) 하위 테이블이 없는 경우, PDF/A 호환성을 유지하기 위해 다른 하위 테이블이 사용됩니다. 사용할 하위 테이블의 선택은 앞서 설명한 규칙에 따라 이루어지며, [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 및 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 속성이 결과 하위 테이블을 결정하는 데 사용되고, 글꼴에 요청된 하위 테이블이 없는 경우 존재하는 다른 하위 테이블이 사용됩니다.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## 생성자

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | 생성자. 기본 하위 테이블(mac 1,0)을 설정합니다. |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | 생성자. |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | 생성자. |

## 속성

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 처리할 인코딩 하위 테이블의 큐를 지정합니다. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | 기본적으로 사용되는 mac subtable(1,0)보다 우선적으로 사용할 하위 테이블을 지정합니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)의 값 'MacTable'은 이 경우 의미가 없습니다. |

### 추가 정보

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)