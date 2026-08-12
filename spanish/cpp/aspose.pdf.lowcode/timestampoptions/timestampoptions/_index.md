---
title: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions constructor"
linktitle: "TimestampOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions constructor. Crea una nueva instancia con valores predeterminados. Se usa para firmar TSA con un archivo PFX en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.lowcode/timestampoptions/timestampoptions/
---
## TimestampOptions::TimestampOptions() constructor


Crea una nueva instancia con valores predeterminados. Se utiliza para firmar TSA con un archivo PFX.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions()
```

## Ver también

* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Crea una nueva instancia con un flujo PFX y contraseña.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::SharedPtr<System::IO::Stream> &pfxStream, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfxStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream que contiene los datos PFX. |
| password | const System::String\& | Contraseña del PFX. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::String\&, const System::String\&) constructor


Crea una nueva instancia con una ruta de archivo PFX y contraseña.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::String &pfxPath, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfxPath | const System::String\& | Ruta al archivo PFX. |
| password | const System::String\& | Contraseña del archivo PFX. |

## Ver también

* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
