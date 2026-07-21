---
title: "Aspose::Pdf::Metered class"
linktitle: "Metered"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Metered class. Proporciona métodos para establecer la clave de tarifa en C++."
type: docs
weight: 11300
url: /es/cpp/aspose.pdf/metered/
---
## Metered class


Proporciona métodos para establecer la clave medida.

```cpp
class Metered : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Obtiene el crédito de consumo. |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo. |
| [GetProductName](./getproductname/)() | Obtenga el nombre del producto. |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Compruebe si el medidor está licenciado. |
| [Metered](./metered/)() | Inicializa una nueva instancia de esta clase. |
| [SetMeteredKey](./setmeteredkey/)(const System::String\&, const System::String\&) | Establece la clave pública y privada de metered. Si compra una licencia metered, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, volver a llamar a esta API. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
