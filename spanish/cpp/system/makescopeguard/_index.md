---
title: "System::MakeScopeGuard método"
linktitle: "CrearGuardiaDeÁmbito"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MakeScopeGuard método. Una función de fábrica que crea instancias de la clase ScopedGuard en C++."
type: docs
weight: 25500
url: /es/cpp/system/makescopeguard/
---
## System::MakeScopeGuard method


Una función de fábrica que crea instancias de la clase ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


| Parámetro | Descripción |
| --- | --- |
| El | tipo del objeto función que será invocado por el objeto ScopedGuard construido |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | F | El objeto función a pasar al constructor de la clase ScopedGuard. |

### ReturnValue

Una nueva instancia de la clase ScopedGuard

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
