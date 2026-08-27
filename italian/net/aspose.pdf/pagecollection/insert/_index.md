---
title: "PageCollection.Insert"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PageCollection. Inserisce una pagina vuota nella raccolta nella posizione specificata. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina."
type: docs
weight: 160
url: /it/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Inserisce una pagina vuota nella raccolta nella posizione specificata. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso in cui vi siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina.

```csharp
public Page Insert(int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Posizione della nuova pagina. |

### Valore di ritorno

Pagina inserita.

### Vedi anche

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Inserisce una pagina nella raccolta di pagine nel punto specificato.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Indice di pagina richiesto nella raccolta. |
| entità | Page | Pagina da inserire. |

### Valore di ritorno

Pagina inserita.

### Vedi anche

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Inserisce pagine dalla raccolta nel documento.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Posizione iniziale delle nuove pagine. |
| pagine | ICollection`1 | Raccolta di pagine. |

### Vedi anche

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Numero iniziale delle nuove pagine. |
| pagine | Page[] | Array di pagine che verranno inserite. |

### Vedi anche

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


