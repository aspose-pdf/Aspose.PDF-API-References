---
title: "System::Collections::Specialized::BitVector32 clase"
linktitle: "BitVector32"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Specialized::BitVector32 clase. Proporciona un vector de bits ligero y simple con acceso fácil a entero o Boolean a un almacenamiento de 32 bits en C++."
type: docs
weight: 100
url: /es/cpp/system.collections.specialized/bitvector32/
---
## BitVector32 class


Proporciona un vector de bits ligero y simple con acceso fácil a entero o [Boolean](../../system/boolean/) a un almacenamiento de 32 bits.

```cpp
class BitVector32
```

## Nested classes

* Class [Section](./section/)
## Métodos

| Método | Descripción |
| --- | --- |
| [BitVector32](./bitvector32/)() | Inicializa una nueva instancia vacía de [BitVector32](./). |
| [BitVector32](./bitvector32/)(int32_t) | Inicializa una nueva instancia de la estructura [BitVector32](./) con los datos internos especificados. |
| [BitVector32](./bitvector32/)(const BitVector32\&) | Inicializa una nueva instancia de la estructura [BitVector32](./) con la información del valor especificado. |
| static [CreateMask](./createmask/)() | Crea la primera máscara de una serie. |
| static [CreateMask](./createmask/)(int32_t) | Crea la siguiente máscara de una serie. |
| static [CreateSection](./createsection/)(int16_t) | Crea la primera sección de una serie, con el valor máximo especificado. |
| static [CreateSection](./createsection/)(int16_t, BitVector32::Section) | Crea la siguiente sección de una serie, con el valor máximo especificado. |
| [Equals](./equals/)(const BitVector32\&) | Determina si el objeto especificado es el mismo que el actual. |
| [get_Data](./get_data/)() | devuelve los datos sin procesar almacenados en este vector de bits... |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [idx_get](./idx_get/)(int32_t) | Obtiene un valor que indica si todos los bits especificados están establecidos. |
| [idx_get](./idx_get/)(BitVector32::Section) | Obtiene el valor de la sección especificada. |
| [idx_set](./idx_set/)(int32_t, bool) | Establece un valor que indica si todos los bits especificados están establecidos. |
| [idx_set](./idx_set/)(BitVector32::Section, int32_t) | Establece el valor de la sección especificada. |
| static [ToString](./tostring/)(const BitVector32\&) | Convierte el valor representado por el parámetro value a cadena. |
| [ToString](./tostring/)() const | Convierte el valor representado por el objeto actual a cadena. |
## Ver también

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
