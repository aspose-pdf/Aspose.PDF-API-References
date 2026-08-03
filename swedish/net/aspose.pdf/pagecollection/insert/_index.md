---
title: "PageCollection.Insert"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PageCollection‑metod. Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med varierande storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas"
type: docs
weight: 160
url: /sv/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Position för den nya sidan. |

### Returvärde

Infogad sida.

### Se även

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Infogar en sida i sidinsamlingen på angiven plats.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Krävt sidindex i samlingen. |
| entitet | Page | Sida som ska infogas. |

### Returvärde

Infogad sida.

### Se även

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
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
| sidor | ICollection`1 | Sidsamling. |

### Se även

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Infogar sidor från arrayen i dokumentet.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Startnummer för de nya sidorna. |
| sidor | Page[] | Array av sidor som kommer att infogas. |

### Se även

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


