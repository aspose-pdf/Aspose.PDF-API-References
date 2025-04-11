---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método PageCollection. Insira uma página vazia na coleção na posição especificada. Se o documento já contiver páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. No caso de haver apenas duas páginas diferentes, o tamanho da primeira página será utilizado.
type: docs
weight: 160
url: /pt/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Insira uma página vazia na coleção na posição especificada. Se o documento já contiver páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. No caso de haver apenas duas páginas diferentes, o tamanho da primeira página será utilizado.

```csharp
public Page Insert(int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Posição da nova página. |

### Valor de Retorno

Página inserida.

### Veja Também

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Insere a página na coleção de páginas no local especificado.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Índice da página requerida na coleção. |
| entity | Page | Página a ser inserida. |

### Valor de Retorno

Página inserida.

### Veja Também

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Insere páginas da coleção no documento.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Posição inicial das novas páginas. |
| pages | ICollection`1 | Coleção de páginas. |

### Veja Também

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Insere páginas do array no documento.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Número inicial das novas páginas. |
| pages | Page[] | Array de páginas que serão inseridas. |

### Veja Também

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)