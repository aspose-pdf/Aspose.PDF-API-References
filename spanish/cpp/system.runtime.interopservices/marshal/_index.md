---
title: "System::Runtime::InteropServices::Marshal clase"
linktitle: "Marshal"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Runtime::InteropServices::Marshal clase. Proporciona una implementación de marshaling. Solo para compatibilidad con el código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio en C++."
type: docs
weight: 100
url: /es/cpp/system.runtime.interopservices/marshal/
---
## Marshal class


Proporciona una implementación de marshaling. Solo para compatibilidad con el código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Marshal
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [AllocHGlobal](./allochglobal/)(int32_t) | Reserva memoria no administrada. |
| static [AllocHGlobal](./allochglobal/)(IntPtr) | Reserva memoria no administrada. |
| static [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementa la semántica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static [Copy](./copy/)(const void *, container\&&, int, int) | Implementa la semántica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static [Copy](./copy/)(const container\&, int, void *, int) | Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static [FreeHGlobal](./freehglobal/)(IntPtr) | Libera memoria no administrada. |
| static [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Convierte un puntero a función no administrado a un delegado de un tipo especificado. |
| static [GetHRForException](./gethrforexception/)(const System::Exception\&) | Obtiene HResult de la excepción. |
| static [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Crea una [String](../../system/string/) administrada a partir de una cadena UTF8 sin terminación nula no administrada. |
| static [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Crea una [String](../../system/string/) administrada a partir de una cadena UTF8 no administrada. |
| static [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Crea una [String](../../system/string/) administrada a partir de una cadena sin terminación nula no administrada. |
| static [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Crea una [String](../../system/string/) administrada a partir de una cadena no administrada. |
| static [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Crea una [String](../../system/string/) administrada a partir de una cadena unicode sin terminación nula no administrada. |
| static [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Crea una [String](../../system/string/) administrada a partir de una cadena unicode no administrada. |
| static [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Crea una [String](../../system/string/) administrada a partir de una cadena UTF8 sin terminación nula no administrada. |
| static [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Crea una [String](../../system/string/) administrada a partir de una cadena UTF8 no administrada. |
| static [ReadByte](./readbyte/)(IntPtr, int) | Lee un byte de la memoria. |
| static [ReadInt16](./readint16/)(IntPtr, int) | Lee un short de la memoria. |
| static [ReadInt32](./readint32/)(IntPtr, int) | Lee un int de la memoria. |
| static [ReadIntPtr](./readintptr/)(IntPtr, int) | Lee un IntPtr de la memoria. |
| static [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const SharedPtr\<Security::SecureString\>\&) | Copia el contenido de la cadena segura especificada a memoria no administrada, convirtiéndolo al formato ANSI. |
| static [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const SharedPtr\<Security::SecureString\>\&) | Copia el contenido de la cadena segura especificada a memoria no administrada. |
| static [StringToHGlobalAnsi](./stringtohglobalansi/)(const String\&) | Copia el contenido de una cadena especificada a memoria no administrada. |
| static [StringToHGlobalAuto](./stringtohglobalauto/)(const String\&) | Copia el contenido de una cadena especificada a memoria no administrada, convirtiéndolo al formato ANSI si es necesario. |
| static [StringToHGlobalUni](./stringtohglobaluni/)(const String\&) | Copia el contenido de una cadena especificada a memoria no administrada. |
| static [WriteByte](./writebyte/)(IntPtr, int, uint8_t) | Escribe un byte en la memoria. |
| static [WriteByte](./writebyte/)(IntPtr, uint8_t) | Escribe un byte en la memoria. |
| static [WriteInt16](./writeint16/)(IntPtr, int, int16_t) | Escribe un short en la memoria. |
| static [WriteInt32](./writeint32/)(IntPtr, int, int32_t) | Escribe un int en la memoria. |
| static [WriteInt64](./writeint64/)(IntPtr, int, int64_t) | Escribe un long en la memoria. |
| static [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Escribe un IntPtr en la memoria. |
| static [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Libera el puntero de cadena no administrada que fue asignado usando el método SecureStringToGlobalAllocAnsi. |
| static [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Libera el puntero de cadena no administrada que fue asignado usando el método SecureStringToGlobalAllocUnicode. |
## Ver también

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.PDF for C++](../../)
