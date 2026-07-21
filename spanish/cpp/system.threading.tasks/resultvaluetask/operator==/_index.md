---
title: "System::Threading::Tasks::ResultValueTask::operator== método"
linktitle: "operator=="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultValueTask::operator== método. Operador de igualdad para ResultValueTask en C++."
type: docs
weight: 1200
url: /es/cpp/system.threading.tasks/resultvaluetask/operator==/
---
## ResultValueTask::operator== method


Operador de igualdad para [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const ResultValueTask\& | El otro [ResultValueTask](../) para comparar con esta instancia. |

### ReturnValue

bool Verdadero si ambas tareas tienen el mismo valor de resultado o hacen referencia a la misma tarea subyacente; de lo contrario, falso.
## Observaciones



Si alguna de las instancias contiene un valor de resultado directo, compara los resultados directamente. De lo contrario, compara los punteros a las tareas subyacentes.
## Ver también

* Class [ResultValueTask](../)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
