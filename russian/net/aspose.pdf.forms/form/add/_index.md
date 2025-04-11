---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Добавляет поле на форму
type: docs
weight: 190
url: /ru/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Добавляет поле на форму.

```csharp
public void Add(Field field, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | Field | Поле, которое должно быть добавлено. |
| pageNumber | Int32 | Индекс страницы, на которой будет размещено добавленное поле. |

### См. также

* класс [Field](../../field/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Добавляет поле на форму.

```csharp
public void Add(Field field)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | Field | Поле, которое должно быть добавлено. |

### См. также

* класс [Field](../../field/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Добавляет новое поле в форму; если это поле уже размещено на другой или этой форме, создается копия поля.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | Field | Имя поля. |
| partialName | String | Имя поля на форме. |
| pageNumber | Int32 | Номер страницы, на которой будет добавлено поле. |

### Возвращаемое значение

Возвращается добавленное поле. Если была создана копия поля, она будет возвращена.

### См. также

* класс [Field](../../field/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)