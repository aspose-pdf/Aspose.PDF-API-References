---
title: "클래스 PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfASymbolicFontEncodingStrategy 클래스. 이 클래스는 TrueType 심볼릭 폰트가 하나 이상의 인코딩을 가질 때 인코딩 데이터를 복사하는 과정을 조정하는 데 사용할 수 있는 규칙을 설명합니다. PDF/A 형식으로 변환된 일부 PDF 문서는 'symbolic TrueType fonts cmap에 인코딩이 둘 이상'이라는 오류를 발생시킬 수 있습니다. 이 오류의 원인은 모든 TrueType 심볼릭 폰트가 내부 데이터에 특수 테이블 cmap을 가지고 있기 때문입니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑합니다. 또한 이 테이블은 사용된 인코딩을 설명하는 다양한 인코딩 서브테이블을 포함할 수 있습니다. cmap 테이블에 대한 자세한 정보는 https//developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html을 참조하십시오. 일반적으로 cmap 테이블에는 여러 인코딩 서브테이블이 포함되지만 PDF/A 표준에서는 해당 폰트에 대해 PDF/A 문서에 하나의 인코딩 서브테이블만 남겨두거나 폰트 서브테이블 중에 30 인코딩 서브테이블이 존재해야 합니다. 여기서 핵심 질문은 어떤 데이터를 다른 서브테이블에서 가져와 대상 인코딩 테이블 30에 복사해야 하는가입니다. 대부분의 폰트는 모든 인코딩 서브테이블이 서로 완전히 일치하는 잘 형성된 cmap 테이블을 가지고 있습니다. 그러나 일부 폰트는 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 서브테이블은 유니코드 100에 대해 글리프 인덱스 100을 가지고 있고 다른 서브테이블은 동일한 유니코드 100에 대해 글리프 인덱스 200을 가지고 있습니다. 이러한 문제를 해결하려면 특수 전략이 필요합니다. 기본적으로 다음 전략이 사용됩니다: mac 서브테이블10을 찾습니다. 이 테이블이 발견되면 해당 데이터만 사용하여 대상 테이블 30을 채웁니다. mac 서브테이블이 없으면 30을 제외한 모든 서브테이블을 순회하며 데이터를 대상 30 서브테이블에 복사합니다. 또한 각 유니코드-글리프 인덱스 매핑은 대상 테이블에 현재 해당 유니코드가 없을 때만 복사됩니다. 따라서 첫 번째 서브테이블에 유니코드 100에 대한 글리프 인덱스 100이 있고 다음 서브테이블에 동일한 유니코드 100에 대한 글리프 인덱스 200이 있더라도 첫 번째 서브테이블의 데이터만 복사됩니다. 즉 이전 서브테이블이 다음 서브테이블보다 우선합니다. 이 클래스 PdfASymbolicFontEncodingStrategy의 속성은 기본 동작을 조정하는 데 도움이 됩니다. 타입이 CMapEncodingTableType인 PreferredCmapEncodingTable 속성이 설정되면 mac 서브테이블10보다 해당 서브테이블이 우선적으로 사용됩니다. CMapEncodingTableType 열거형의 MacTable 값은 기본적으로 사용되는 동일한 mac 서브테이블10을 가리키므로 이 경우 의미가 없습니다. CmapEncodingTablesPriorityQueue 속성은 모든 서브테이블에 대한 우선순위를 무시합니다. 이 속성이 설정되면 선언된 큐에 있는 서브테이블만 지정된 순서대로 사용됩니다. 지정된 서브테이블이 없으면 모든 서브테이블을 기본 순회하고 위에서 설명한 복사 전략을 사용합니다. 객체 QueueItem은 사용되는 인코딩 서브테이블을 지정합니다. 이 서브테이블은 membersPlatformID, PlatformSpecificId의 조합이나 CMapEncodingTableType 열거형을 통해 설정될 수 있습니다. 폰트에 30 서브테이블이 없을 경우 다른 서브테이블이 PDF/A 호환성을 유지하기 위해 사용됩니다. 사용할 서브테이블 선택은 앞서 설명한 동일한 규칙에 따라 이루어지며, PreferredCmapEncodingTable 및 CmapEncodingTablesPriorityQueue 속성을 사용해 최종 서브테이블을 결정하고, 요청된 서브테이블이 없으면 존재하는 어떤 서브테이블이든 사용됩니다."
type: docs
weight: 8470
url: /ko/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy class

이 클래스는 TrueType 심볼릭 폰트에 인코딩이 둘 이상 있는 경우 인코딩 데이터를 복사하는 과정을 조정하는 데 사용할 수 있는 규칙을 설명합니다. PDF 문서를 PDF/A 형식으로 변환한 후 일부 문서에서 "More than one encoding in symbolic TrueType font's cmap" 오류가 발생할 수 있습니다. 이 오류의 원인은 무엇일까요? 모든 TrueType 심볼릭 폰트는 내부 데이터에 특별한 "cmap" 테이블을 가지고 있습니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑합니다. 또한 이 테이블은 사용된 인코딩을 설명하는 다양한 인코딩 서브테이블을 포함할 수 있습니다. cmap 테이블에 대한 자세한 내용은 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html 를 참고하십시오. 일반적으로 cmap 테이블에는 여러 인코딩 서브테이블이 포함되지만 PDF/A 표준에서는 이 폰트에 대해 PDF/A 문서에 하나의 인코딩 서브테이블만 남겨두거나 해당 폰트 서브테이블 중에 (3,0) 인코딩 서브테이블이 있어야 합니다. 여기서 핵심 질문은 - (3,0) 대상 인코딩 테이블에 복사하기 위해 다른 서브테이블에서 어떤 데이터를 가져와야 하는가입니다. 대부분의 폰트는 모든 인코딩 서브테이블이 서로 완전히 일치하는 'well-formed' cmap 테이블을 가지고 있습니다. 그러나 일부 폰트는 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 서브테이블은 유니코드 100에 대해 글리프 인덱스 100을 가지고 있지만 다른 서브테이블은 동일한 유니코드 100에 대해 글리프 인덱스 200을 가지고 있습니다. 이러한 문제를 해결하려면 특별한 전략이 필요합니다. 기본적으로 다음 전략이 사용됩니다: mac 서브테이블(1,0)을 찾습니다. 이 테이블이 발견되면 해당 데이터만 사용하여 대상 테이블(3,0)을 채웁니다. mac 서브테이블이 없으면 (3,0)을 제외한 모든 서브테이블을 순회하면서 대상(3,0) 서브테이블에 데이터를 복사합니다. 또한 각 유니코드(유니코드, 글리프 인덱스) 매핑은 대상 테이블에 현재 해당 유니코드가 없을 때만 복사됩니다. 따라서 예를 들어 첫 번째 서브테이블이 유니코드 100에 대해 글리프 인덱스 100을 가지고 있고, 다음 서브테이블이 동일한 유니코드 100에 대해 글리프 인덱스 200을 가지고 있다면, 첫 번째 서브테이블의 데이터(유니코드=100, 글리프 인덱스=100)만 복사됩니다. 즉 이전 서브테이블이 다음 서브테이블보다 우선합니다. 이 클래스 `PdfASymbolicFontEncodingStrategy`의 속성은 기본 동작을 조정하는 데 도움이 됩니다. 속성 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/)의 타입이 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)인 경우, mac 서브테이블(1,0)보다 우선적으로 해당 서브테이블이 사용됩니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)의 값 'MacTable'은 이 경우 의미가 없으며, 기본적으로 사용되는 mac 서브테이블(1,0)과 동일하기 때문입니다. 속성 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/)은 모든 서브테이블에 대한 우선순위를 무시합니다. 이 속성이 설정되면 선언된 큐에 있는 서브테이블만 지정된 순서대로 사용됩니다. 지정된 서브테이블이 없으면 모든 서브테이블을 기본 순서대로 순회하고 위에서 설명한 복사 전략이 사용됩니다. 객체 [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/)은 사용될 인코딩 서브테이블을 지정합니다. 이 서브테이블은 멤버(PlatformID, PlatformSpecificId)의 조합이나 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 열거형을 통해 설정할 수 있습니다. 폰트에 (3,0) 서브테이블이 없을 경우 다른 서브테이블이 PDF/A 호환성을 유지하기 위해 사용됩니다. 사용될 서브테이블 선택은 앞서 설명한 동일한 규칙에 따라 이루어지며, [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 및 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 속성이 결과 서브테이블을 결정하는 데 사용되고, 폰트에 요청된 서브테이블이 없으면 존재하는 어떤 서브테이블이든 사용됩니다.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | 생성자. 기본 서브테이블(mac 1,0)을 설정합니다. |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | 생성자 |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 처리할 인코딩 서브테이블 큐를 지정합니다. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | mac 서브테이블(1,0)보다 우선적으로 사용될 서브테이블을 지정합니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)의 값 'MacTable'은 이 경우 의미가 없습니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


