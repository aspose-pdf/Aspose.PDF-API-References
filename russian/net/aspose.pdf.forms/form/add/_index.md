---
title: "Form.Add"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Добавляет поле в форму."
type: docs
weight: 210
url: /ru/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Добавляет поле в форму.

```csharp
public void Add(Field field, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поле | Поле | Поле, которое должно быть добавлено. |
| pageNumber | Int32 | Индекс страницы, на которой будет размещено добавленное поле. |

### См. также

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Добавляет поле в форму.

```csharp
public void Add(Field field)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поле | Поле | Поле, которое должно быть добавлено. |

### См. также

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Добавляет новое поле в форму; если это поле уже размещено в другой или в этой форме, создаётся копия поля.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поле | Поле | Имя поля. |
| partialName | String | Имя поля в форме. |
| pageNumber | Int32 | Номер страницы, на которой будет добавлено поле. |

### Возвращаемое значение

Возвращено добавленное поле. Если была создана копия поля, она будет возвращена.

### См. также

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


