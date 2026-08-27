---
title: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이 클래스는 TrueType 심볼릭 폰트에 둘 이상의 인코딩이 있을 경우 인코딩 데이터를 복사하는 과정을 조정할 수 있는 규칙을 설명합니다. 일부 PDF 문서를 PDF/A 형식으로 변환한 후 'Symbolic TrueType fonts cmap에 인코딩이 둘 이상 존재합니다'라는 오류가 발생할 수 있습니다. 이 오류의 원인은 모든 TrueType 심볼릭 폰트가 내부 데이터에 특수한 cmap 테이블을 가지고 있기 때문입니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑합니다. 또한 이 테이블은 사용된 인코딩을 설명하는 다양한 인코딩 서브테이블을 포함할 수 있습니다. cmap 테이블에 대한 자세한 내용은 https//developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html 를 참조하십시오. 일반적으로 cmap 테이블은 여러 인코딩 서브테이블을 포함하지만 PDF/A 표준에서는 이 폰트에 대해 하나의 인코딩 서브테이블 30만 남겨야 합니다. 여기서 핵심 질문은 다른 서브테이블에서 어떤 데이터를 가져와 대상 인코딩 테이블 30에 복사해야 하는가 입니다. 대부분의 폰트는 모든 인코딩 서브테이블이 서로 완전히 일치하는 잘 형성된 cmap 테이블을 가지고 있습니다. 그러나 일부 폰트는 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 서브테이블은 유니코드 100에 대해 글리프 인덱스 100을 갖고 다른 서브테이블은 동일한 유니코드 100에 대해 글리프 인덱스 200을 갖는 경우가 있습니다. 이러한 문제를 해결하려면 특수한 전략이 필요합니다. 기본적으로는 mac subtable10을 찾는 전략이 사용됩니다. 이 테이블이 발견되면 해당 데이터만 사용하여 대상 테이블 30을 채웁니다. mac subtable이 없을 경우 30을 제외한 모든 서브테이블을 순회하며 데이터를 대상 30 서브테이블에 복사합니다. 또한 각 unicodeunicode 글리프 인덱스 매핑은 대상 테이블에 현재 해당 유니코드가 없을 때만 복사됩니다. 따라서 예를 들어 첫 번째 서브테이블이 유니코드 100에 대해 글리프 인덱스 100을 가지고 두 번째 서브테이블이 동일한 유니코드 100에 대해 글리프 인덱스 200을 가지고 있으면 첫 번째 서브테이블의 데이터(유니코드 100 글리프 인덱스 100)만 복사됩니다. 이렇게 이전 서브테이블이 다음 서브테이블보다 우선합니다. 이 클래스 PdfASymbolicFontEncodingStrategy의 속성은 기본 동작을 조정하는 데 도움이 됩니다. PreferredCmapEncodingTable 속성이 CMapEncodingTableType 유형으로 설정되면 해당 서브테이블이 mac subtable10보다 우선적으로 사용됩니다. 열거형 CMapEncodingTableType의 값 MacTable은 기본값인 mac subtable10과 동일한 서브테이블을 가리키므로 이 경우 의미가 없습니다. CmapEncodingTablesPriorityQueue 속성은 모든 서브테이블에 대한 우선순위를 무시합니다. 이 속성이 설정되면 선언된 큐에 있는 서브테이블만 지정된 순서대로 사용됩니다. 지정된 서브테이블이 없으면 모든 서브테이블을 기본 순서대로 순회하고 위에서 설명한 복사 전략을 사용합니다. QueueItem 객체는 사용될 인코딩 서브테이블을 지정합니다. 이 서브테이블은 membersPlatformID, PlatformSpecificId 조합이나 CMapEncodingTableType 열거형을 통해 설정할 수 있습니다."
type: docs
weight: 1190
url: /ko/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---

## PdfASymbolicFontEncodingStrategy class

이 클래스는 TrueType 심볼릭 폰트에 인코딩이 둘 이상 존재하는 경우 복사 인코딩 데이터를 조정하는 데 사용할 수 있는 규칙을 설명합니다.<br/>            PDF 문서를 PDF/A 형식으로 변환한 후 일부 PDF 문서에서 "More than one encoding in symbolic TrueType font's cmap" 오류가 발생할 수 있습니다.<br/>            이 오류의 원인은 무엇일까요? 모든 TrueType 심볼릭 폰트는 내부 데이터에 특수 테이블 "cmap"을 가지고 있습니다. 이 테이블은 문자 코드를 글리프 인덱스로 매핑합니다.<br/>            그리고 이 테이블은 사용된 인코딩을 설명하는 다양한 인코딩 서브테이블을 포함할 수 있습니다. cmap 테이블에 대한 자세한 정보는 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html 에서 확인하십시오.<br/>            일반적으로 cmap 테이블은 여러 인코딩 서브테이블을 포함하지만, PDF/A 표준에서는 이 폰트에 대해 (3,0) 하나의 인코딩 서브테이블만 남겨야 합니다.<br/>            여기서 핵심 질문은 - 다른 서브테이블에서 어떤 데이터를 가져와 대상 인코딩 테이블 (3,0) 에 복사해야 하는가 입니다. 대부분의 폰트는 모든 인코딩 서브테이블이 서로 완전히 일치하는 'well-formed' cmap 테이블을 가지고 있습니다. 그러나 일부 폰트는 충돌이 있는 cmap 테이블을 가지고 있는데, 예를 들어 한 서브테이블은 유니코드 100에 대해 글리프 인덱스 100을 가지고, 다른 서브테이블은 동일한 유니코드 100에 대해 글리프 인덱스 200을 가지고 있습니다.<br/>            이러한 문제를 해결하려면 특수한 전략이 필요합니다.<br/>            기본적으로 다음 전략이 사용됩니다:<br/>            mac 서브테이블(1,0)을 찾습니다. 이 테이블이 발견되면 해당 데이터만 사용하여 대상 테이블 (3,0)을 채웁니다. mac 서브테이블이 없으면 (3,0)을 제외한 모든 서브테이블을 순회하며 데이터를 대상 (3,0) 서브테이블에 복사합니다. 또한 각 유니코드(유니코드, 글리프 인덱스) 매핑은 대상 테이블에 현재 해당 유니코드가 없을 때만 복사됩니다.<br/>            예를 들어 첫 번째 서브테이블에 유니코드 100에 대해 글리프 인덱스 100이 있고, 다음 서브테이블에 동일한 유니코드 100에 대해 글리프 인덱스 200이 있다면, 첫 번째 서브테이블(유니코드=100, 글리프 인덱스=100)의 데이터만 복사됩니다.<br/>            따라서 이전 서브테이블이 다음 서브테이블보다 우선합니다.<br/>            이 클래스의 속성인 [PdfASymbolicFontEncodingStrategy](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/)은 기본 동작을 조정하는 데 도움이 됩니다.<br/>            타입이 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/)인 속성 [preferred_cmap_encoding_table](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/)이 설정되면, 해당 서브테이블이 mac 서브테이블(1,0)보다 우선적으로 사용됩니다. 열거형 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/)의 값 'MacTable'은 이 경우 의미가 없으며, 기본적으로 사용되는 동일한 mac 서브테이블(1,0)을 가리킵니다.<br/>            속성 [None](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/)은 모든 서브테이블에 대한 우선순위를 무시합니다.<br/>            이 속성이 설정되면 선언된 큐에 있는 서브테이블만 지정된 순서대로 사용됩니다.<br/>            지정된 서브테이블이 없을 경우, 위에서 설명한 기본 모든 서브테이블 순회 및 복사 전략이 사용됩니다.<br/>            객체 [QueueItem](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy/queueitem/)는 사용되는 인코딩 서브테이블을 지정합니다. 이 서브테이블은 멤버(PlatformID, PlatformSpecificId)의 조합이나 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) 열거형을 통해 설정할 수 있습니다.

PdfASymbolicFontEncodingStrategy 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfASymbolicFontEncodingStrategy() | 생성자. 기본 서브테이블(mac 1,0)을 설정합니다. |
| PdfASymbolicFontEncodingStrategy(preferred_encoding_table) | PdfASymbolicFontEncodingStrategy 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| preferred_cmap_encoding_table | mac 서브테이블(1,0)보다 우선적으로 사용될 서브테이블을 지정합니다. 값 'MacTable'은<br/>            열거형 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/)에서 가져온 것으로, 이 경우 의미가 없습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

