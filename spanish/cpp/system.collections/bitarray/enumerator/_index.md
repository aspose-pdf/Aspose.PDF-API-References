---
title: "System::Collections::BitArray::Enumerator clase"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::BitArray::Enumerator clase. Tipo enumerador para propósitos de iteración en C++."
type: docs
weight: 2900
url: /es/cpp/system.collections/bitarray/enumerator/
---
## Enumerator class


[Enumerator](./) type for iteration purposes.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<bool>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<BitArray\>\&) | Crea un enumerador. |
| [get_Current](./get_current/)() const override | Obtiene el bit direccionado en forma booleana. |
| [MoveNext](./movenext/)() override | Se mueve al siguiente bit. |
| [Reset](./reset/)() override | Restablece el enumerador a la posición anterior al primer elemento. |
## Ver también

* Class [Object](../../../system/object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [BitArray](../)
* Namespace [System::Collections](../../)
* Library [Aspose.PDF for C++](../../../)
