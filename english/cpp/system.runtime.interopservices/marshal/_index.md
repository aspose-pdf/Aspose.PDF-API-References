---
title: System::Runtime::InteropServices::Marshal class
linktitle: Marshal
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::InteropServices::Marshal class. Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 100
url: /cpp/system.runtime.interopservices/marshal/
---
## Marshal class


Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Marshal
```

## Methods

| Method | Description |
| --- | --- |
| static [AllocHGlobal](./allochglobal/)(int32_t) | Allocates unmanaged memory. |
| static [AllocHGlobal](./allochglobal/)(IntPtr) | Allocates unmanaged memory. |
| static [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implements public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics. |
| static [Copy](./copy/)(const void *, container\&&, int, int) | Implements public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics. |
| static [Copy](./copy/)(const container\&, int, void *, int) | Implements public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static [Copy](./copy/)(const container\&, int, IntPtr, int) | Implements public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static [FreeHGlobal](./freehglobal/)(IntPtr) | Frees unmanaged memory. |
| static [GetHRForException](./gethrforexception/)(const System::Exception\&) | Gets HResult from exception. |
| static [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated UTF8-string. |
| static [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged UTF8-string. |
| static [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated string. |
| static [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged string. |
| static [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated unicode string. |
| static [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged unicode string. |
| static [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated UTF8-string. |
| static [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged UTF8-string. |
| static [ReadByte](./readbyte/)(IntPtr, int) | Reads byte from memory. |
| static [ReadInt16](./readint16/)(IntPtr, int) | Reads short from memory. |
| static [ReadInt32](./readint32/)(IntPtr, int) | Reads int from memory. |
| static [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const SharedPtr\<Security::SecureString\>\&) | Copies contents of specified secure string into unmanaged memory, converting into ANSI format. |
| static [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const SharedPtr\<Security::SecureString\>\&) | Copies contents of specified secure string into unmanaged memory. |
| static [StringToHGlobalAnsi](./stringtohglobalansi/)(const String\&) | Copies the contents of a specified string into unmanaged memory. |
| static [StringToHGlobalAuto](./stringtohglobalauto/)(const String\&) | Copies the contents of a specified string into unmanaged memory, converting to ANSI format if required. |
| static [StringToHGlobalUni](./stringtohglobaluni/)(const String\&) | Copies the contents of a specified string into unmanaged memory. |
| static [WriteByte](./writebyte/)(IntPtr, int, uint8_t) | Writes byte to memory. |
| static [WriteByte](./writebyte/)(IntPtr, uint8_t) | Writes byte to memory. |
| static [WriteInt16](./writeint16/)(IntPtr, int, int16_t) | Writes short to memory. |
| static [WriteInt32](./writeint32/)(IntPtr, int, int32_t) | Writes int to memory. |
| static [WriteInt64](./writeint64/)(IntPtr, int, int64_t) | Writes long to memory. |
| static [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Frees unmanaged string pointer that was allocated using the SecureStringToGlobalAllocAnsi method. |
| static [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Frees unmanaged string pointer that was allocated using the SecureStringToGlobalAllocUnicode method. |
## See Also

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.PDF for C++](../../)
