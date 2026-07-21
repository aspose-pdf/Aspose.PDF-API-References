---
title: "System::IO::STDIOStreamPositionPreference enum"
linktitle: "STDIOStreamPositionPreference"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::STDIOStreamPositionPreference enum. Determina qué posición en el flujo es preferible como posición común de lectura y escritura cuando std::basic_iostream y sus descendientes tendrán diferentes posiciones de lectura y escritura en el momento de la creación del contenedor en C++."
type: docs
weight: 3600
url: /es/cpp/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum


Determina qué posición en el flujo es preferible como posición común de lectura y escritura cuando std::basic_iostream y sus descendientes tendrán diferentes posiciones de lectura y escritura en el momento de crear el envoltorio.

```cpp
enum class STDIOStreamPositionPreference
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Cero | 0 | La posición cero se establecerá como posición de lectura y escritura. |
| ReadPosition | 1 | La posición gptr se establecerá como posición de lectura y escritura. |
| WritePosition | 2 | La posición pptr se establecerá como posición de lectura y escritura. |

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
