---
title: Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions constructor
linktitle: TimestampOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions constructor. Creates a new instance with default values. Used to sing TSA with a PFX file in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.lowcode/timestampoptions/timestampoptions/
---
## TimestampOptions::TimestampOptions() constructor


Creates a new instance with default values. Used to sing TSA with a PFX file.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions()
```

## See Also

* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Creates a new instance with a PFX stream and password.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::SharedPtr<System::IO::Stream> &pfxStream, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfxStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream containing the PFX data. |
| password | const System::String\& | Password for the PFX. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::String\&, const System::String\&) constructor


Creates a new instance with a PFX file path and password.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::String &pfxPath, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfxPath | const System::String\& | Path to the PFX file. |
| password | const System::String\& | Password for the PFX file. |

## See Also

* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
