---
title: Save
second_title: Aspose.PDF для справочника API .NET
description: Сохранить документ инкрементно т. е. используя метод инкрементного обновления.
type: docs
weight: 720
url: /ru/net/aspose.pdf/document/save/
---
## Save() {#save}

Сохранить документ инкрементно (т. е. используя метод инкрементного обновления).

```csharp
public void Save()
```

### Примечания

Чтобы сохранить документ постепенно, мы должны открыть файл документа для записи. Следовательно, Document должен быть инициализирован потоком, доступным для записи, как в следующем фрагменте кода: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите некоторые изменения и сохраните документ incrementally doc.Save();

### Смотрите также

* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Сохраняет документ с параметрами сохранения.

```csharp
public void Save(SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Сохранить параметры. |

### Смотрите также

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| format | SaveFormat | Параметры формата. |

### Смотрите также

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, где документ будет храниться. |
| format | SaveFormat | Параметры формата. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException когда[`HtmlSaveOptions`](../../htmlsaveoptions) передается методу. Сохранение документа в поток html не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### Смотрите также

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Сохраняет документ с новым именем, задавая параметры сохранения.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| options | SaveOptions | Сохранить параметры. |

### Смотрите также

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Сохраняет документ в поток с параметрами сохранения.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, где документ будет храниться. |
| options | SaveOptions | Сохранить параметры. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException когда[`HtmlSaveOptions`](../../htmlsaveoptions) передается методу. Сохранение документа в поток html не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### Смотрите также

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Сохраняет документ в поток ответов с параметрами сохранения.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| response | HttpResponse | Инкапсулирует информацию HTTP-ответа. |
| outputFileName | String | Простое имя файла, т.е. без пути. |
| disposition | ContentDisposition | Представляет заголовок Content-Disposition протокола MIME. |
| options | SaveOptions | Сохранить параметры. |

### Смотрите также

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Сохраняет документ в потоке.

```csharp
public void Save(Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | Stream | Поток, где будет храниться оболочка документа. |

### Смотрите также

* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Сохраняет документ в указанный файл.

```csharp
public void Save(string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |

### Смотрите также

* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
