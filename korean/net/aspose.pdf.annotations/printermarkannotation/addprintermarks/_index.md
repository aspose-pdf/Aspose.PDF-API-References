---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation 메서드. 지정된 문서의 모든 페이지에 프린터 마크를 추가합니다.
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
| document | Document | 프린터 마크가 추가될 문서입니다. |
| marksKind | PrinterMarksKind | 추가할 프린터 마크의 종류입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *document*가 null일 때 발생합니다. |

## 비고

이 메서드는 제공된 [`PrinterMarksKind`](../../printermarkskind/) 플래그에 따라 다양한 유형의 프린터 마크를 추가합니다. None이 제공되면 마크가 추가되지 않습니다.

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 열거형 [PrinterMarksKind](../../printermarkskind/)
* 클래스 [PrinterMarkAnnotation](../)
* 네임스페이스 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

지정된 페이지에 프린터 마크를 추가합니다.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Page | 프린터 마크가 추가될 페이지입니다. |
| marksKind | PrinterMarksKind | 추가할 프린터 마크의 종류입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *page*가 null일 때 발생합니다. |

## 비고

이 메서드는 제공된 [`PrinterMarksKind`](../../printermarkskind/) 플래그에 따라 다양한 유형의 프린터 마크를 추가합니다. None이 제공되면 마크가 추가되지 않습니다.

### 참조

* 클래스 [Page](../../../aspose.pdf/page/)
* 열거형 [PrinterMarksKind](../../printermarkskind/)
* 클래스 [PrinterMarkAnnotation](../)
* 네임스페이스 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../../)