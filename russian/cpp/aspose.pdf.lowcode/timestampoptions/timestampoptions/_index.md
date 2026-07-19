---
title: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions конструктор"
linktitle: "TimestampOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions конструктор. Создает новый экземпляр со значениями по умолчанию. Используется для подписи TSA с файлом PFX в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.lowcode/timestampoptions/timestampoptions/
---
## TimestampOptions::TimestampOptions() constructor


Создаёт новый экземпляр со значениями по умолчанию. Используется для подписи TSA с файлом PFX.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions()
```

## См. также

* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Создаёт новый экземпляр с потоком PFX и паролем.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::SharedPtr<System::IO::Stream> &pfxStream, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfxStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные PFX. |
| password | const System::String\& | Пароль для PFX. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::String\&, const System::String\&) constructor


Создаёт новый экземпляр с путём к файлу PFX и паролем.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::String &pfxPath, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfxPath | const System::String\& | Путь к файлу PFX. |
| password | const System::String\& | Пароль для файла PFX. |

## См. также

* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
