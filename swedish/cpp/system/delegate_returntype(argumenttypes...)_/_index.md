---
title: "System::Delegate< ReturnType(ArgumentTypes...)> klass"
linktitle: "Delegate< ReturnType(ArgumentTypes...)>"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Delegate< ReturnType(ArgumentTypes...)> klass. Representerar en pekare till en funktion, metod eller ett funktionsobjekt. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 2200
url: /sv/cpp/system/delegate_returntype(argumenttypes...)_/
---
## Delegate< ReturnType(ArgumentTypes...)> class


Representerar en pekare till en funktion, metod eller ett funktionsobjekt. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parameter | Beskrivning |
| --- | --- |
| ReturnType | Returtypen för en funktion, metod eller ett funktionsobjekt som pekaren representeras av klassen |
| ArgumentTypes | Argumentlistan för en funktion, metod eller ett funktionsobjekt som pekaren representeras av klassen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Delegate](./delegate/)() | Standardkonstruktor. Skapar delegatobjektet som inte pekar på någonting. |
| [Delegate](./delegate/)(const Delegate\&) |  |
| [Delegate](./delegate/)(Delegate\&&) | Flyttkopieringskonstruktor. Tar äganderätten till en entitet som pekas på av den angivna delegaten. |
| [Delegate](./delegate/)(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Skapar ett delegatobjekt från den angivna pekaren till en fri funktion eller statisk metod. |
| [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Skapar en delegat från den angivna pekaren till funktionsobjektet som genererats av std::bind(). |
| [Delegate](./delegate/)(int, T\&) | Konstruktor. Skapar en delegat från det angivna funktionsobjektet. |
| [Delegate](./delegate/)(long, T\&&) | Flyttkonstruktor. Skapar en delegat från det angivna funktionsobjektet. |
| [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden för det angivna objektet. |
| [Delegate](./delegate/)(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) | Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden för det angivna objektet. |
| [Delegate](./delegate/)(std::function\<R(Args...)>) | Skapar ett delegatobjekt som pekar på ett std::function-funktionsobjekt. |
| [Empty](./empty/)() const | Bestämmer om det aktuella delegatobjektet är tomt, t.ex. inte pekar på någon entitet. |
| [operator()](./operator()/)(ArgumentTypes...) const | Invokerar en funktion, metod eller ett funktionsobjekt som pekas på av det aktuella delegatobjektet. |
| [operator=](./operator=/)(const Delegate\&) |  |
| [operator=](./operator=/)(Delegate\&&) | Flytttilldelningsoperator. Tar äganderätten till en entitet som pekas på av den angivna delegaten. |
| [operator==](./operator==/)(const Delegate\&) const | Jämför två delegatobjekt för att kontrollera om de pekar på samma entitet. |
## Anmärkningar



```cpp
#include "system/delegate.h"
#include <iostream>

// Deklarera delegaten.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Tilldela variabeln adressen till PrintMessage-funktionen.
  Message mes = Message(&PrintMessage);

  // Anropa funktionen.
  mes();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
