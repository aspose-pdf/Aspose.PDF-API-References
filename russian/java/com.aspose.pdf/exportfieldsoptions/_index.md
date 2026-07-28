---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет базовый класс параметров для экспорта полей формы."
type: docs
weight: 1310
url: /ru/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Представляет базовый класс параметров для экспорта полей формы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Получает или задаёт значение, указывающее, следует ли экспортировать значение пароля. Значение: {@code true}, если значение пароля должно быть экспортировано; иначе {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Получает делегат, определяющий, следует ли экспортировать конкретное поле. Если делегат равен {@code null}, экспортируются все поля (поведение по умолчанию). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Получает или задаёт значение, указывающее, следует ли экспортировать значение пароля. Значение: {@code true}, если значение пароля должно быть экспортировано; иначе {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Задаёт делегат, определяющий, следует ли экспортировать конкретное поле. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Получает или задаёт значение, указывающее, следует ли экспортировать значение пароля. Значение: {@code true}, если значение пароля должно быть экспортировано; иначе {@code false}.

**Returns:**
логическое значение

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Получает делегат, определяющий, следует ли экспортировать конкретное поле. Если делегат равен {@code null}, экспортируются все поля (поведение по умолчанию).

**Returns:**
делегат, определяющий, следует ли экспортировать конкретное поле.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Получает или задаёт значение, указывающее, следует ли экспортировать значение пароля. Значение: {@code true}, если значение пароля должно быть экспортировано; иначе {@code false}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Задаёт делегат, определяющий, следует ли экспортировать конкретное поле.
