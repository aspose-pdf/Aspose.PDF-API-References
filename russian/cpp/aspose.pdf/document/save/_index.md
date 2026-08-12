---
title: "Aspose::Pdf::Document::Save метод"
linktitle: "Сохранить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document::Save метод. Сохраняет документ инкрементально (т. е. используя технику инкрементного обновления) в C++."
type: docs
weight: 8300
url: /ru/cpp/aspose.pdf/document/save/
---
## Document::Save() method


Сохраняет документ инкрементно (т.е. используя технику инкрементного обновления).

```cpp
void Aspose::Pdf::Document::Save()
```

## Примечания


Чтобы сохранить документ инкрементально, необходимо открыть файл документа для записи. Поэтому [Document](../) должен быть инициализирован записываемым потоком, как в следующем фрагменте кода: [Document](../) doc = new [Document](../)(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите некоторые изменения и сохраните документ инкрементально doc.Save();
## См. также

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<SaveOptions\>\&) method


Сохраняет документ с параметрами сохранения.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<SaveOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | const System::SharedPtr\<SaveOptions\>\& | Параметры сохранения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&) method


Сохраняет документ в поток.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет храниться оболочка документа. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) method


Сохраняет документ в поток с параметрами сохранения.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<SaveOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён документ. |
| опции | const System::SharedPtr\<SaveOptions\>\& | Параметры сохранения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) method


Сохраняет документ под новым именем вместе с форматом файла.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, SaveFormat format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён документ. |
| формат | SaveFormat | Параметры формата. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) method


Сохраняет документ в поток ответа с параметрами сохранения.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::Web::HttpResponse> &response, const System::String &outputFileName, ContentDisposition disposition, const System::SharedPtr<SaveOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Инкапсулирует информацию HTTP-ответа. |
| outputFileName | const System::String\& | Простое имя файла, т.е. без пути. |
| disposition | ContentDisposition | Представляет заголовок MIME-протокола Content-Disposition. |
| опции | const System::SharedPtr\<SaveOptions\>\& | Параметры сохранения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [String](../../../system/string/)
* Enum [ContentDisposition](../../contentdisposition/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&) method


Сохраняет документ в указанный файл.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | const System::String\& | Путь к файлу, где будет сохранён документ. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) method


Сохраняет документ под новым именем, задавая его параметры сохранения.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, const System::SharedPtr<SaveOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | const System::String\& | Путь к файлу, где будет сохранён документ. |
| опции | const System::SharedPtr\<SaveOptions\>\& | Параметры сохранения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, SaveFormat) method


Сохраняет документ под новым именем вместе с форматом файла.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, SaveFormat format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | const System::String\& | Путь к файлу, где будет сохранён документ. |
| формат | SaveFormat | Параметры формата. |

## См. также

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
