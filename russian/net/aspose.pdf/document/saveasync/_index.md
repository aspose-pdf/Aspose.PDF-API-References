---
title: "Document.SaveAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Document. Сохраняет документ в поток с параметрами сохранения"
type: docs
weight: 860
url: /ru/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Сохраняет документ в поток с параметрами сохранения.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранён документ. |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException когда [`HtmlSaveOptions`](../../htmlsaveoptions/) передается методу. Сохранение документа в html‑поток не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### См. также

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Сохраняет документ в поток.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | Stream | Поток, в котором будет храниться документ. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Сохраняет документ в указанный файл.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Сохранять документ инкрементно (т.е. используя технику инкрементного обновления).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

## Примечания

Чтобы сохранить документ инкрементно, необходимо открыть файл документа для записи. Поэтому Document должен быть инициализирован записываемым потоком, как в следующем фрагменте кода: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите некоторые изменения и сохраните документ инкрементно doc.Save();

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Сохраняет документ с параметрами сохранения.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| формат | SaveFormat | Параметры формата. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранён документ. |
| формат | SaveFormat | Параметры формата. |
| cancellationToken | CancellationToken | Токен отмены |

### Возвращаемое значение

Асинхронная задача.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException когда [`HtmlSaveOptions`](../../htmlsaveoptions/) передается методу. Сохранение документа в html‑поток не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### См. также

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Сохраняет документ под новым именем, задавая его параметры сохранения.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


