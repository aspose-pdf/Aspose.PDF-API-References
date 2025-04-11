---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Проверьте, есть ли в форме уже указано поле
type: docs
weight: 280
url: /ru/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Проверьте, есть ли в форме уже указано поле.

```csharp
public bool HasField(Field field)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | Field | Поле для проверки. |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в форму; в противном случае `false`.

### См. также

* класс [Field](../../field/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Определяет, добавлено ли поле с указанным именем в форму.

```csharp
public bool HasField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) или [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) поля. |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в форму; в противном случае `false`.

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Определяет, добавлено ли поле с указанным именем в форму, с возможностью поиска в иерархии дочерних полей.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) или [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) поля. |
| searchChildren | Boolean | Если установлено в `true`, будет выполнен поиск по всей иерархии полей формы для запрашиваемого *fieldName* (обратите внимание, что в этом случае [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) требуемого поля должен быть передан как *fieldName*). |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в форму; в противном случае `false`.

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)