---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem 클래스. 인코딩 서브테이블을 지정합니다. 각 인코딩 서브테이블은 매개변수 PlatformID, PlatformSpecificId의 고유한 조합을 가집니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 및 속성 [`CMapEncodingTable`](./cmapencodingtable/)는 필요한 인코딩 서브테이블 세트를 쉽게 설정할 수 있도록 구현되었습니다.
type: docs
weight: 8340
url: /ko/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem 클래스

인코딩 서브테이블을 지정합니다. 각 인코딩 서브테이블은 매개변수 (PlatformID, PlatformSpecificId)의 고유한 조합을 가집니다. 열거형 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 및 속성 [`CMapEncodingTable`](./cmapencodingtable/)는 필요한 인코딩 서브테이블 세트를 쉽게 설정할 수 있도록 구현되었습니다.

```csharp
public class QueueItem
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | 생성자, 기본적으로 mac 서브테이블(1,0)을 지정합니다 |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | 생성자 |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 열거형을 통해 인코딩 서브테이블을 지정합니다 |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | 인코딩 서브테이블의 플랫폼 식별자 |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | 인코딩 서브테이블의 플랫폼별 인코딩 식별자 |

### 참조

* 클래스 [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)