---
title: "Form.HasField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Проверяет, содержит ли форма уже указанное поле."
type: docs
weight: 300
url: /ru/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Проверьте, содержит ли форма уже указанное поле.

```csharp
public bool HasField(Field field)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поле | Поле | Поле для проверки. |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в Form; иначе `false`.

### См. также

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Определяет, добавлено ли поле с указанным именем уже в форму.

```csharp
public bool HasField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) или [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) поля. |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в Form; иначе `false`.

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Определяет, добавлено ли поле с указанным именем уже в форму, с возможностью просматривать иерархию дочерних полей.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) или [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) поля. |
| searchChildren | Boolean | Когда установлено `true`, будет выполнен поиск по всей иерархии полей формы для запрошенного *fieldName* (обратите внимание, что в этом случае [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) требуемого поля должно быть передано как *fieldName*). |

### Возвращаемое значение

`true`, если указанное имя поля добавлено в Form; иначе `false`.

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


