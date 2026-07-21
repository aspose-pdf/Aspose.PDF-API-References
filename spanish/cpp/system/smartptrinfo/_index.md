---
title: "System::SmartPtrInfo clase"
linktitle: "SmartPtrInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::SmartPtrInfo clase. Clase de servicio para probar y alterar el contenido de SmartPtr sin conocer el tipo final. Utilizada para recolección de basura y detección de referencias en bucle, etc. Piense en ella como un ''puntero a puntero''. No podemos usar el tipo base de SmartPtr ya que no tiene ninguno; en su lugar, usamos esta clase ''info'' en C++."
type: docs
weight: 5900
url: /es/cpp/system/smartptrinfo/
---
## SmartPtrInfo class


Clase de servicio para probar y alterar el contenido de [SmartPtr](../smartptr/)'s sin conocer el tipo final. Utilizada para recolección de basura y detección de referencias en bucle, etc. Piense en ella como un 'puntero a puntero'. No podemos usar el tipo base de [SmartPtr](../smartptr/)'s ya que no tiene ninguno; en su lugar, usamos esta clase 'info'.

```cpp
class SmartPtrInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [getInternalPtr](./getinternalptr/)() const | Obtiene el puntero al objeto crudo referenciado. |
| [getObject](./getobject/)() const | Obtiene el puntero al objeto referenciado. |
| [getOwned](./getowned/)() const | Obtiene el puntero propietario del objeto. |
| [operator bool](./operatorbool/)() const | Comprueba si el objeto info apunta a un puntero no nulo. |
| [operator!](./operator!/)() const | Comprueba si el objeto info no apunta a un puntero no nulo. |
| [operator->](./operator-_/)() const | Permite llamar a los métodos de [Object](../object/) apuntado por el puntero referenciado. |
| [operator<](./operator_/)(const SmartPtrInfo\&) const | Compara menores los valores de los punteros referenciados por dos objetos info. |
| [SmartPtrInfo](./smartptrinfo/)() | Crea un objeto [SmartPtrInfo](./) vacío. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const SmartPtr\<T\>\&) | Crea un objeto [SmartPtrInfo](./) con información sobre un puntero inteligente específico. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
