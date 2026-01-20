---
title: Aspose::Pdf::License::SetLicense method
linktitle: SetLicense
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::License::SetLicense method. Licenses the component in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/license/setlicense/
---
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licenses the component.

```cpp
void Aspose::Pdf::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | A stream that contains the license. |
## Remarks



Use this method to load a license from a stream.

[Java] void setLicense(java.io.InputStream stream) 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## License::SetLicense(System::String) method


Licenses the component.

```cpp
void Aspose::Pdf::License::SetLicense(System::String licenseName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | System::String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |
## Remarks


Tries to find the license in the following locations:

1. Explicit path.

2. The folder that contains the **Aspose** component assembly.

3. The folder that contains the client's calling assembly.

4. The folder that contains the entry (startup) assembly.

5. An embedded resource in the client's calling assembly.

**[Note](../../note/):**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

[Java] 

2. The folder that contains the **Aspose** component JAR file.

3. The folder that contains the client's calling JAR file.

## See Also

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
