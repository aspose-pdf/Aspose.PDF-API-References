---
title: Aspose::Pdf::TimestampSettings::TimestampSettings constructor
linktitle: TimestampSettings
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TimestampSettings::TimestampSettings constructor. Initializes a new instance of the TimestampSettings class in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/timestampsettings/timestampsettings/
---
## TimestampSettings::TimestampSettings constructor


Initializes a new instance of the [TimestampSettings](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::TimestampSettings::TimestampSettings(System::String serverUrl, System::String basicAuthCredentials, Aspose::Pdf::DigestHashAlgorithm digestHashAlgorithm=Aspose::Pdf::DigestHashAlgorithm::Sha1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| serverUrl | System::String | The timestamp server url. |
| basicAuthCredentials | System::String | The basic authentication credentials, username and password are combined into a string "username:password". |
| digestHashAlgorithm | Aspose::Pdf::DigestHashAlgorithm | The hash algorithm name, if it is omitted then sha1 is used. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>serverUrl</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The timestamp server url.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>basicAuthCredentials</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The basic authentication credentials, username and password are combined into a string "username:password".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>digestHashAlgorithm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The hash algorithm name, if it is omitted then sha1 is used.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [DigestHashAlgorithm](../../digesthashalgorithm/)
* Class [TimestampSettings](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
