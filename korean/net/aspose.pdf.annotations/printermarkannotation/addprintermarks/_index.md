---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PrinterMarkAnnotation 메서드. 지정된 문서의 모든 페이지에 프린터 마크를 추가합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

지정된 문서의 모든 페이지에 프린터 마크를 추가합니다.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | Document | 프린터 마크가 추가될 문서. |
| marksKind | PrinterMarksKind | 추가할 프린터 마크의 종류. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *document*가 null인 경우 발생합니다. |

## 비고

이 메서드는 제공된 [`PrinterMarksKind`](../../printermarkskind/) 플래그를 기반으로 다양한 유형의 프린터 마크를 추가합니다. None이 제공되면 마크가 추가되지 않습니다.

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

지정된 페이지에 프린터 마크를 추가합니다.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | 프린터 마크가 추가될 페이지. |
| marksKind | PrinterMarksKind | 추가할 프린터 마크의 종류. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *page*가 null인 경우 발생합니다. |

## 비고

이 메서드는 제공된 [`PrinterMarksKind`](../../printermarkskind/) 플래그를 기반으로 다양한 유형의 프린터 마크를 추가합니다. None이 제공되면 마크가 추가되지 않습니다.

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


