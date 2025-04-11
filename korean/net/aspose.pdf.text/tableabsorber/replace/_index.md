---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber 메서드. 페이지에서 AbsorbedTable을 Table로 교체합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace 메서드

페이지에서 [`AbsorbedTable`](../../absorbedtable/)을 [`Table`](../../../aspose.pdf/table/)로 교체합니다.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Page | Pdf 문서 페이지 객체. |
| oldTable | AbsorbedTable | 교체할 [`AbsorbedTable`](../../absorbedtable/)입니다. |
| newTable | Table | 이전 테이블을 교체할 [`Table`](../../../aspose.pdf/table/)입니다. |

## 비고

TableList 컬렉션이 변경된다는 점을 고려해 주십시오. 루프에서 테이블을 제거하거나 교체하는 경우 TableList 컬렉션의 복사본을 사용하십시오.

### 참조

* 클래스 [Page](../../../aspose.pdf/page/)
* 클래스 [AbsorbedTable](../../absorbedtable/)
* 클래스 [Table](../../../aspose.pdf/table/)
* 클래스 [TableAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)