---
title: "ComHelper.OpenFile"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод ComHelper. Просто создаёт и возвращает Document, используя имя файла. То же, что и Document"
type: docs
weight: 20
url: /ru/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Просто создаёт и возвращает Document, используя *filename*. То же, что и [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла pdf‑документа. |

### Возвращаемое значение

Объект Document

### См. также

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Инициализирует и возвращает новый экземпляр класса [`Document`](../../document/) для работы с зашифрованным документом.

```csharp
public Document OpenFile(string filename, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |

### Возвращаемое значение

Объект Document

### См. также

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Инициализирует новый экземпляр класса [`Document`](../../document/) для работы с зашифрованным документом.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### Возвращаемое значение

Объект Document

### См. также

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Откройте существующий документ из файла, предоставив необходимые параметры конвертации для получения PDF‑документа.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Входной файл для преобразования в pdf‑документ. |
| options | LoadOptions | Представляет свойства для преобразования *filename* в PDF‑документ. |

### Возвращаемое значение

Объект Document

### См. также

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


