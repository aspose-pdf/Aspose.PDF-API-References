---
title: "PageCollection.Insert"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PageCollection. Вставляет пустую page в коллекцию в указанной позиции. Если документ уже содержит pages разных размеров, будет выбран размер наиболее часто встречающейся page. В случае, когда существует только две разные pages, будет использован размер первой page."
type: docs
weight: 160
url: /ru/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Вставить пустую страницу в коллекцию в указанную позицию. Если документ уже содержит страницы разного размера, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы.

```csharp
public Page Insert(int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Позиция новой page. |

### Возвращаемое значение

Вставленная page.

### См. также

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Вставляет страницу в коллекцию страниц в указанное место.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Требуемый page индекс в коллекции. |
| сущность | Страница | Page для вставки. |

### Возвращаемое значение

Вставленная page.

### См. также

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Вставляет страницы из коллекции в документ.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Начальная позиция новых pages. |
| страницы | ICollection`1 | Коллекция Pages. |

### См. также

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Вставляет страницы из массива в документ.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Начальное количество новых pages. |
| страницы | Page[] | Массив pages, которые будут вставлены. |

### См. также

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


