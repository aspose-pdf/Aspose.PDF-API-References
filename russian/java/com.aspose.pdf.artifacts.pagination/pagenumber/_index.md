---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет формат номера страницы, включающий индекс, общее количество страниц и разделитель."
type: docs
weight: 150
url: /ru/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Представляет формат номера страницы, включающий индекс, общее количество страниц и разделитель.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Получает или задает разделитель, используемый в формате номера страницы. Отформатированная строка будет обновлена в соответствии с указанным разделителем. |
| [getIndex](#getIndex--) | Получает или задает компонент индекса страницы в формате номера страницы. Отформатированная строка будет включать заполнитель для индекса страницы. |
| [getOffset](#getOffset--) | Получает или задает смещение, которое будет добавлено к индексу страницы. |
| [getPageNumberString](#getPageNumberString-int-int-) | Возвращает отформатированную строку, представляющую номер страницы на основе текущих настроек. |
| [getTotalNum](#getTotalNum--) | Получает или задает компонент общего количества страниц в формате номера страницы. Отформатированная строка будет включать заполнитель для общего количества страниц. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Получает или задает разделитель, используемый в формате номера страницы. Отформатированная строка будет обновлена в соответствии с указанным разделителем. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Получает или задает компонент индекса страницы в формате номера страницы. |
| [setOffset](#setOffset-int-) | Получает или задает смещение, которое будет добавлено к индексу страницы. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Получает или задает компонент общего количества страниц в формате номера страницы. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Получает или задает разделитель, используемый в формате номера страницы. Отформатированная строка будет обновлена в соответствии с указанным разделителем.

**Returns:**
строковое значение

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Получает или задает компонент индекса страницы в формате номера страницы. Отформатированная строка будет включать заполнитель для индекса страницы.

**Returns:**
Экземпляр PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

Получает или задает смещение, которое будет добавлено к индексу страницы.

**Returns:**
int значение

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Возвращает отформатированную строку, представляющую номер страницы на основе текущих настроек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber |  | Текущий номер страницы. |
| количество |  | Общее количество страниц. |

**Returns:**
Отформатированная строка номера страницы.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Получает или задает компонент общего количества страниц в формате номера страницы. Отформатированная строка будет включать заполнитель для общего количества страниц.

**Returns:**
Экземпляр PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
Получает или задает разделитель, используемый в формате номера страницы. Отформатированная строка будет обновлена в соответствии с указанным разделителем.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Получает или задает компонент индекса страницы в формате номера страницы.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Получает или задает смещение, которое будет добавлено к индексу страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Получает или задает компонент общего количества страниц в формате номера страницы.
