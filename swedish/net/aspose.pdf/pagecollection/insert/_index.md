---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection-metod. Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med varierande storlekar kommer storleken på den mest frekvent förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas.
type: docs
weight: 160
url: /sv/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med varierande storlekar, kommer storleken på den mest frekvent förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Position för den nya sidan. |

### Returvärde

Infogad sida.

### Se Även

* klass [Page](../../page/)
* klass [PageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Infogar sidan i sidinsamlingen på angiven plats.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Obligatorisk sidindex i samlingen. |
| entity | Page | Sida som ska infogas. |

### Returvärde

Infogad sida.

### Se Även

* klass [Page](../../page/)
* klass [PageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Infogar sidor från samlingen i dokumentet.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Startposition för de nya sidorna. |
| pages | ICollection`1 | Sidsamling. |

### Se Även

* klass [Page](../../page/)
* klass [PageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Infogar sidorna i arrayen i dokumentet.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Startnummer för de nya sidorna. |
| pages | Page[] | Array av sidor som kommer att infogas. |

### Se Även

* klass [Page](../../page/)
* klass [PageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)