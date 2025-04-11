---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Метод PageCollection. Вставить пустую страницу в коллекцию в указанной позиции. Если документ уже содержит страницы с различными размерами, будет выбрана размер наиболее часто встречающейся страницы. В случае, если есть только две разные страницы, будет использован размер первой страницы.
type: docs
weight: 160
url: /ru/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Вставить пустую страницу в коллекцию в указанной позиции. Если документ уже содержит страницы с различными размерами, будет выбрана размер наиболее часто встречающейся страницы. В случае, если есть только две разные страницы, будет использован размер первой страницы.

```csharp
public Page Insert(int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Позиция новой страницы. |

### Возвращаемое значение

Вставленная страница.

### См. также

* класс [Page](../../page/)
* класс [PageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Вставляет страницу в коллекцию страниц в указанном месте.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Индекс требуемой страницы в коллекции. |
| entity | Page | Страница, которую нужно вставить. |

### Возвращаемое значение

Вставленная страница.

### См. также

* класс [Page](../../page/)
* класс [PageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Вставляет страницы из коллекции в документ.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Начальная позиция новых страниц. |
| pages | ICollection`1 | Коллекция страниц. |

### См. также

* класс [Page](../../page/)
* класс [PageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Вставляет страницы массива в документ.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Начальный номер новых страниц. |
| pages | Page[] | Массив страниц, которые будут вставлены. |

### См. также

* класс [Page](../../page/)
* класс [PageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)