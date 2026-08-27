---
title: "Document.Save"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Document. Сохраняет документ в поток с параметрами сохранения"
type: docs
weight: 850
url: /ru/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

Сохраняет документ в поток с параметрами сохранения.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранён документ. |
| options | SaveOptions | Параметры сохранения. |

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

## Save(Stream) {#save_2}

Сохраняет документ в поток.

```csharp
public void Save(Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | Stream | Поток, в котором будет храниться документ. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Сохраняет документ в указанный файл.

```csharp
public void Save(string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Сохранять документ инкрементно (т.е. используя технику инкрементного обновления).

```csharp
public void Save()
```

## Примечания

Чтобы сохранить документ инкрементно, необходимо открыть файл документа для записи. Поэтому Document должен быть инициализирован записываемым потоком, как в следующем фрагменте кода: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите некоторые изменения и сохраните документ инкрементно doc.Save();

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Сохраняет документ с параметрами сохранения.

```csharp
public void Save(SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Параметры сохранения. |

### См. также

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| формат | SaveFormat | Параметры формата. |

### См. также

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Сохраняет документ под новым именем вместе с форматом файла.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будет сохранён документ. |
| формат | SaveFormat | Параметры формата. |

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

## Save(string, SaveOptions) {#save_7}

Сохраняет документ под новым именем, задавая его параметры сохранения.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в котором будет храниться документ. |
| options | SaveOptions | Параметры сохранения. |

### См. также

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


