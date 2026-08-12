---
title: "Класс Aspose::Pdf::Facades::AutoFiller"
linktitle: "AutoFiller"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::AutoFiller. Представляет класс, получающий данные из базы данных или другого источника данных, заполняющий их в предназначенные поля шаблонного PDF и в конце генерирующий новый PDF‑файл или поток. Имеет два режима ввода шаблонного файла: ввод как поток или как PDF‑файл. Имеет четыре типа режимов вывода: один объединённый поток, один объединённый файл, множество небольших потоков, множество небольших файлов. Может принимать буквальные данные, содержащиеся в объекте System.Data.DataTable в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.facades/autofiller/
---
## AutoFiller class


Представляет класс, получающий данные из базы данных или другого источника данных, заполняющий их в предназначенные поля шаблонного PDF и в конце генерирующий новый PDF‑файл или поток. Имеет два режима ввода шаблонного файла: ввод как поток или как PDF‑файл. Имеет четыре типа режимов вывода: один объединённый поток, один объединённый файл, множество небольших потоков, множество небольших файлов. Может принимать буквальные данные, содержащиеся в [System.Data.DataTable](../../system.data/datatable/).

```cpp
class AutoFiller : public Aspose::Pdf::Facades::ISaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [AutoFiller](./autofiller/)() |  |
| [BindPdf](./bindpdf/)(System::String) override | Привязывает файл [Pdf](../../aspose.pdf/). |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Привязывает файл [Pdf](../../aspose.pdf/). |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Document\>) override | Привязывает документ [Pdf](../../aspose.pdf/). |
| [Close](./close/)() override | Закрывает объект и потоки вывода. |
| [Dispose](./dispose/)() override | Закрывает объект и потоки вывода. |
| [get_BasicFileName](./get_basicfilename/)() const | Получает базовое имя файла, если будет генерировано много небольших файлов. Сгенерированный файл будет выглядеть как "BasicFileName0","BasicFileName1",... Это работает с другим свойством [GeneratingPath](../)GeneratingPath. |
| [get_GeneratingPath](./get_generatingpath/)() const | Получает путь генерации небольших pdf‑файлов, если будет генерировано много небольших pdf‑файлов. Это работает с другим свойством [BasicFileName](../)BasicFileName. Один из четырёх режимов вывода. |
| [get_InputFileName](./get_inputfilename/)() const | Получает файл шаблона ввода. Один из двух режимов ввода. |
| [get_InputStream](./get_inputstream/)() const | Получает поток шаблона ввода. Один из двух режимов ввода. |
| [get_OutputFileName](./get_outputfilename/)() const | Получает один большой объединённый файл вывода. Один из четырёх режимов вывода. |
| [get_OutputStream](./get_outputstream/)() const | Получает OutputStream. Один из четырёх режимов вывода. Его классический пример использования — Response.OutputStream. Пожалуйста, обратитесь к онлайн‑демо. |
| [get_OutputStreams](./get_outputstreams/)() const | Получает множество Output Streams. Один из четырёх режимов вывода. |
| [Save](./save/)() | Сохраняет все pdf‑файлы. |
| [Save](./save/)(System::String) override | Сохраняет все pdf‑файлы. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет все pdf‑файлы. |
| [set_BasicFileName](./set_basicfilename/)(const System::String\&) | Устанавливает базовое имя файла, если будет генерировано много небольших файлов. Сгенерированный файл будет выглядеть как "BasicFileName0","BasicFileName1",... Это работает с другим свойством [GeneratingPath](../)GeneratingPath. |
| [set_GeneratingPath](./set_generatingpath/)(const System::String\&) | Устанавливает путь генерации небольших pdf‑файлов, если будет генерировано много небольших pdf‑файлов. Это работает с другим свойством [BasicFileName](../)BasicFileName. Один из четырёх режимов вывода. |
| [set_InputFileName](./set_inputfilename/)(const System::String\&) | Устанавливает файл шаблона ввода. Один из двух режимов ввода. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает поток шаблона ввода. Один из двух режимов ввода. |
| [set_OutputFileName](./set_outputfilename/)(const System::String\&) | Устанавливает один большой объединённый файл вывода. Один из четырёх режимов вывода. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает OutputStream. Один из четырёх режимов вывода. Его классический пример использования — Response.OutputStream. Пожалуйста, обратитесь к онлайн‑демо. |
| [set_OutputStreams](./set_outputstreams/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Устанавливает множество Output Streams. Один из четырёх режимов вывода. |
| [set_UnFlattenFields](./set_unflattenfields/)(const System::ArrayPtr\<System::String\>\&) | Устанавливает поля, которые не будут уплощены. Если это свойство не задано, все поля будут уплощены. |
## См. также

* Class [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
