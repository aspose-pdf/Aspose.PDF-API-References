---
title: "System::IO::UnmanagedMemoryStream‑klass"
linktitle: "UnmanagedMemoryStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::UnmanagedMemoryStream‑klass. Tillhandahåller åtkomst till ohanterat minne. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2800
url: /sv/cpp/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream class


Tillhandahåller åtkomst till ohanterat minne. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Flush](./flush/)() override | Gör ingenting. |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| virtual [get_Capacity](./get_capacity/)() const | Returnerar den aktuella kapaciteten för den underliggande minnesbufferten. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [get_PositionPointer](./get_positionpointer/)() | INTE IMPLEMENTERAD. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Ställer in strömmens position. |
| [set_PositionPointer](./set_positionpointer/)(uint8_t *) | INTE IMPLEMENTERAD. |
| [SetLength](./setlength/)(int64_t) override | INTE IMPLEMENTERAD. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t) | Skapar en ny instans av [UnmanagedMemoryStream](./). |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t, int64_t, FileAccess) | Skapar en ny instans av [UnmanagedMemoryStream](./). |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | INTE IMPLEMENTERAD. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | INTE IMPLEMENTERAD. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
