---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Metodo PageCollection. Inserisci una pagina vuota nella collezione nella posizione specificata. Se il documento contiene già pagine di dimensioni diverse, verrà selezionata la dimensione della pagina più frequentemente occorrente. Nel caso ci siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina.
type: docs
weight: 160
url: /it/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Inserisci una pagina vuota nella collezione nella posizione specificata. Se il documento contiene già pagine di dimensioni diverse, verrà selezionata la dimensione della pagina più frequentemente occorrente. Nel caso ci siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Posizione della nuova pagina. |

### Return Value

Pagina inserita.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Inserisce la pagina nella collezione di pagine nel luogo specificato.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Indice della pagina richiesto nella collezione. |
| entity | Page | Pagina da inserire. |

### Return Value

Pagina inserita.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Inserisce le pagine dalla collezione nel documento.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Posizione di partenza delle nuove pagine. |
| pages | ICollection`1 | Collezione di pagine. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Inserisce le pagine dell'array nel documento.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numero di partenza delle nuove pagine. |
| pages | Page[] | Array di pagine che verranno inserite. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)