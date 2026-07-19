---
title: "Класс Aspose::Pdf::TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::TeXLoadOptions. Представляет параметры для загрузки/импорта TeX‑файла в PDF‑документ в C++."
type: docs
weight: 18100
url: /ru/cpp/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class


Представляет параметры загрузки/импорта файла TeX в документ PDF.

```cpp
class TeXLoadOptions : public Aspose::Pdf::LoadOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_DateTime](./get_datetime/)() | Получает/устанавливает определённое значение для примитивов даты/времени, таких как год, месяц, день и время. |
| [get_InputDirectory](./get_inputdirectory/)() | Получает/устанавливает каталог входных данных TeX. |
| [get_JobName](./get_jobname/)() const | Получает/устанавливает имя задания. |
| [get_NoLigatures](./get_noligatures/)() | Получает/устанавливает флаг, отменяющий лигатуры во всех шрифтах. |
| [get_OutputDirectory](./get_outputdirectory/)() | Получает/устанавливает каталог выходных данных TeX. |
| [get_RasterizeFormulas](./get_rasterizeformulas/)() | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [get_Repeat](./get_repeat/)() | Получает/устанавливает флаг, указывающий, необходимо ли запускать задание TeX дважды в случае, например, когда во входных TeX‑файлах есть ссылки. Как правило, такое поведение полезно, когда движок собирает некоторые данные в процессе наборa и сохраняет их во вспомогательный файл при первом запуске. А при втором запуске движок каким‑то образом использует эти данные. |
| [get_RequiredInputDirectory](./get_requiredinputdirectory/)() | Получает/устанавливает требуемый каталог входных данных TeX. Требуемый ввод — это файлы, которые каким‑то образом включаются в основной .tex‑файл, например, пакеты, для которых нет встроенной поддержки. |
| [get_ShowTerminalOutput](./get_showterminaloutput/)() const | Получает/устанавливает флаг, указывающий, показывать ли вывод терминала в консоли. |
| [get_SubsetFonts](./get_subsetfonts/)() | Получает/устанавливает флаг, указывающий, выполнять ли субсетирование шрифтов в выходном файле. |
| [GetLoadResult](./getloadresult/)() | Получает результат загрузки и компиляции TeX — прошёл ли процесс без проблем или были какие‑либо замечания/ошибки. |
| [set_DateTime](./set_datetime/)(System::DateTime) | Получает/устанавливает определённое значение для примитивов даты/времени, таких как год, месяц, день и время. |
| [set_InputDirectory](./set_inputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Получает/устанавливает каталог входных данных TeX. |
| [set_JobName](./set_jobname/)(const System::String\&) | Получает/устанавливает имя задания. |
| [set_NoLigatures](./set_noligatures/)(bool) | Получает/устанавливает флаг, отменяющий лигатуры во всех шрифтах. |
| [set_OutputDirectory](./set_outputdirectory/)(const System::SharedPtr\<ITeXOutputDirectory\>\&) | Получает/устанавливает каталог выходных данных TeX. |
| [set_RasterizeFormulas](./set_rasterizeformulas/)(bool) | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [set_Repeat](./set_repeat/)(bool) | Получает/устанавливает флаг, указывающий, необходимо ли запускать задание TeX дважды в случае, например, когда во входных TeX‑файлах есть ссылки. Как правило, такое поведение полезно, когда движок собирает некоторые данные в процессе наборa и сохраняет их во вспомогательный файл при первом запуске. А при втором запуске движок каким‑то образом использует эти данные. |
| [set_RequiredInputDirectory](./set_requiredinputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Получает/устанавливает требуемый каталог входных данных TeX. Требуемый ввод — это файлы, которые каким‑то образом включаются в основной .tex‑файл, например, пакеты, для которых нет встроенной поддержки. |
| [set_ShowTerminalOutput](./set_showterminaloutput/)(bool) | Получает/устанавливает флаг, указывающий, показывать ли вывод терминала в консоли. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Получает/устанавливает флаг, указывающий, выполнять ли субсетирование шрифтов в выходном файле. |
| [TeXLoadOptions](./texloadoptions/)() | Создаёт параметры загрузки по умолчанию для преобразования TeX‑файла в PDF‑документ. |
## См. также

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
