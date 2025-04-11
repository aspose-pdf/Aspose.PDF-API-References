---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection-Methode. Fügen Sie eine leere Seite an der angegebenen Position in die Sammlung ein. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls nur zwei verschiedene Seiten vorhanden sind, wird die Größe der ersten Seite verwendet.
type: docs
weight: 160
url: /de/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Fügen Sie eine leere Seite an der angegebenen Position in die Sammlung ein. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls nur zwei verschiedene Seiten vorhanden sind, wird die Größe der ersten Seite verwendet.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Position der neuen Seite. |

### Rückgabewert

Eingefügte Seite.

### Siehe auch

* Klasse [Page](../../page/)
* Klasse [PageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Fügt eine Seite an der angegebenen Stelle in die Seitensammlung ein.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Erforderlicher Seitenindex in der Sammlung. |
| entity | Page | Zu insertierende Seite. |

### Rückgabewert

Eingefügte Seite.

### Siehe auch

* Klasse [Page](../../page/)
* Klasse [PageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Fügt Seiten aus der Sammlung in das Dokument ein.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Startposition der neuen Seiten. |
| pages | ICollection`1 | Seitenkollektion. |

### Siehe auch

* Klasse [Page](../../page/)
* Klasse [PageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Fügt Seiten des Arrays in das Dokument ein.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Startnummer der neuen Seiten. |
| pages | Page[] | Array von Seiten, die eingefügt werden. |

### Siehe auch

* Klasse [Page](../../page/)
* Klasse [PageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)