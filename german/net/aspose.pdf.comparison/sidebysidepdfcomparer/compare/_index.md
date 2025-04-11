---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer-Methode. Vergleicht zwei Seiten. Das Ergebnis wird in einem PDF-Dokument gespeichert, in dem die erste Seite zuerst geschrieben wird und dann die zweite. Sie können es in Adobe Acrobat im Zwei-Seiten-Ansicht öffnen, um die Änderungen nebeneinander zu sehen. Löschungen werden auf der linken Seite und Einfügungen auf der rechten Seite vermerkt.
type: docs
weight: 10
url: /de/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Vergleicht zwei Seiten. Das Ergebnis wird in einem PDF-Dokument gespeichert, in dem die erste Seite zuerst geschrieben wird und dann die zweite. Sie können es in Adobe Acrobat im Zwei-Seiten-Ansicht öffnen, um die Änderungen nebeneinander zu sehen. Löschungen werden auf der linken Seite und Einfügungen auf der rechten Seite vermerkt.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page1 | Page | Die erste Seite, die verglichen werden soll. |
| page2 | Page | Die zweite Seite, die verglichen werden soll. |
| targetPdfPath | String | Der Pfad zur PDF-Datei, um ein Vergleichsergebnis zu speichern. |
| options | SideBySideComparisonOptions | Die Vergleichsoptionen. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Klasse [SideBySidePdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Vergleicht zwei Dokumente. Die Seiten werden nacheinander verglichen. Die Seiten der verglichenen Dokumente werden nacheinander in das resultierende Dokument kopiert. Zuerst die erste Seite aus dem ersten Dokument, dann die erste Seite aus dem zweiten Dokument. Als nächstes die zweite Seite aus dem ersten Dokument und dann die zweite Seite aus dem zweiten Dokument, usw. Sie können es in Adobe Acrobat im Zwei-Seiten-Ansicht öffnen, um die Änderungen nebeneinander zu sehen. Löschungen werden auf der linken Seite und Einfügungen auf der rechten Seite vermerkt.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Das erste Dokument, das verglichen werden soll. |
| document2 | Document | Das zweite Dokument, das verglichen werden soll. |
| targetPdfPath | String | Der Pfad zur PDF-Datei, um ein Vergleichsergebnis zu speichern. |
| options | SideBySideComparisonOptions | Die Vergleichsoptionen. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Klasse [SideBySidePdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)