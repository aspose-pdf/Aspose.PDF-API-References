---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection-Klasse. Sammlung von PDF-Dokumentseiten
type: docs
weight: 8080
url: /de/net/aspose.pdf/pagecollection/
---
## Klasse PageCollection

Sammlung von PDF-Dokumentseiten.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Gibt die Anzahl der Seiten im Dokument zurück. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Gibt den Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Gibt die Seite nach Index zurück. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Gibt das Synchronisationsobjekt der Sammlung zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Akzeptiert das [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) Besucherobjekt, das Funktionen zum Arbeiten mit Anmerkungen bereitstellt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Akzeptiert das [`ImagePlacementAbsorber`](../imageplacementabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Akzeptiert das [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Akzeptiert das [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Im Falle von nur zwei unterschiedlichen Seiten wird die Größe der ersten Seite verwendet. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Fügt der Sammlung alle Seiten aus der Liste hinzu. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Fügt der Sammlung eine Seite hinzu. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Fügt der Sammlung alle Seiten aus dem Array hinzu. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Löscht die Seitenkollektion. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Bestimmt, ob diese Instanz das Objekt enthält. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Kopiert Seiten in das Dokument. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Löscht alle Seiten aus der Sammlung. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Löscht die angegebene Seite. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Löscht die Seiten, deren Nummern im Array angegeben sind. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Entfernt alle Felder, die sich auf den Seiten befinden, und platziert deren Werte stattdessen. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Löscht zwischengespeicherte Daten |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Gibt den Enumerator der Seiten zurück. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Gibt den Index der angegebenen Seite zurück. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Fügt an der angegebenen Position eine leere Seite in die Sammlung ein. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Im Falle von nur zwei unterschiedlichen Seiten wird die Größe der ersten Seite verwendet. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Fügt Seiten aus der Sammlung in das Dokument ein. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Fügt die Seite an der angegebenen Stelle in die Seitenkollektion ein. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Fügt die Seiten des Arrays in das Dokument ein. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Entfernt das angegebene Element, wirft NotSupportedException. |

### Siehe auch

* Klasse [Page](../page/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)