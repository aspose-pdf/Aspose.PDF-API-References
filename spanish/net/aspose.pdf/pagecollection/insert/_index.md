---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método PageCollection. Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas de diferentes tamaños, se seleccionará el tamaño de la página que más frecuentemente ocurre. En el caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página.
type: docs
weight: 160
url: /es/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas de diferentes tamaños, se seleccionará el tamaño de la página que más frecuentemente ocurre. En el caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Posición de la nueva página. |

### Return Value

Página insertada.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Inserta la página en la colección de páginas en el lugar especificado.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Índice de página requerido en la colección. |
| entity | Page | Página a ser insertada. |

### Return Value

Página insertada.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Inserta páginas de la colección en el documento.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Posición inicial de las nuevas páginas. |
| pages | ICollection`1 | Colección de páginas. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Inserta las páginas del arreglo en el documento.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Número inicial de las nuevas páginas. |
| pages | Page[] | Arreglo de páginas que serán insertadas. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)