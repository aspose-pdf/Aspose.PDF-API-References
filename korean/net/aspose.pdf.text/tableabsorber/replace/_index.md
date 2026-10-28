---
title: "TableAbsorber.Replace"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TableAbsorber 메서드. 페이지에서 AbsorbedTable을 Table로 교체합니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

페이지에서 [`AbsorbedTable`](../../absorbedtable/)을 [`Table`](../../../aspose.pdf/table/)로 교체합니다.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | Pdf 문서 페이지 객체. |
| oldTable | AbsorbedTable | 교체될 [`AbsorbedTable`](../../absorbedtable/). |
| newTable | Table | 기존 표를 교체할 [`Table`](../../../aspose.pdf/table/). |

## 비고

TableList 컬렉션이 변경된다는 점을 고려하십시오. 루프에서 표를 제거하거나 교체하는 경우 TableList 컬렉션의 복사본을 사용하십시오.

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


