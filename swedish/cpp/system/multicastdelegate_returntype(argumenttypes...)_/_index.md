---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> class"
linktitle: "MulticastDelegate< ReturnType(ArgumentTypes...)>"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> klass. Representerar en samling delegater. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 4700
url: /sv/cpp/system/multicastdelegate_returntype(argumenttypes...)_/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> class


Representerar en samling delegater. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parameter | Beskrivning |
| --- | --- |
| ReturnType | Returtyp för de anropbara enheterna som varje delegat i samlingen pekar på |
| ArgumentTypes | Argumentlista för de anropbara enheterna som varje delegat i samlingen pekar på |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BeginInvoke](./begininvoke/)(ArgumentTypes..., const AsyncCallback\&, const CallbackArgumentType\&) | INTE IMPLEMENTERAD. |
| [connect](./connect/)(Callback) | Lägger till den angivna delegaten i samlingen. |
| [connect](./connect/)(std::function\<R(Args...)>) | Lägger till det angivna funktionsobjektet i delegatsamlingen. Funktionsobjektet konverteras till [Callback](./callback/) delegattype innan det läggs till i samlingen. |
| [connect](./connect/)(MulticastDelegate\&) | Lägger till det angivna MulticastDelegate-objektet i delegatsamlingen. |
| [connect](./connect/)(MemberType ClassType::*, ClassType *) | Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen. |
| [connect](./connect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen. |
| [disconnect](./disconnect/)(Callback) | Tar bort den angivna delegaten från delegatsamlingen. |
| [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen. |
| [disconnect](./disconnect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen. |
| [disconnect](./disconnect/)(MulticastDelegate\&) | Tar bort det angivna MulticastDelegate-objektet från delegatsamlingen. |
| [disconnect_all_slots](./disconnect_all_slots/)() | Tar bort alla delegater från delegatsamlingen. |
| [empty](./empty/)() const | Avgör om delegatsamlingen är tom. |
| [EndInvoke](./endinvoke/)(const SharedPtr\<IAsyncResult\>\&) | INTE IMPLEMENTERAD. |
| [Equals](./equals/)(const MulticastDelegate\&) |  |
| [GetHashCode](./gethashcode/)() const |  |
| [GetType](./gettype/)() const |  |
| [invoke](./invoke/)(ArgumentTypes...) const | Invokar alla delegater som för närvarande finns i delegatsamlingen. Delegaterna invokas i samma ordning som de lades till i samlingen. Metoden blockerar medan delegaterna körs. |
| [IsNull](./isnull/)() const | Avgör om delegatsamlingen är tom. |
| [MulticastDelegate](./multicastdelegate/)() | Skapar en tom samling. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Motsvarar standardkonstruktorn. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Utför en ytlig kopiering av delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Flyttkonstruktör. |
| [MulticastDelegate](./multicastdelegate/)(Callback\&&) | Skapar en instans och placerar den angivna delegaten i delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)(T) | Skapar en instans och placerar det angivna värdet i delegatsamlingen. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Skapar en instans och placerar det angivna värdet i delegatsamlingen. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Avgör om delegatsamlingen inte är tom. |
| [operator!=](./operator!=/)(const MulticastDelegate\&) const | Avgör om två instanser av MulticastDelegate – det aktuella objektet och det angivna objektet – är ojämlika. |
| [operator()](./operator()/)(ArgumentTypes...) const | Invokar alla delegater som för närvarande finns i delegatsamlingen. Delegaterna invokas i samma ordning som de lades till i samlingen. Operatorn blockerar medan delegaterna körs. |
| [operator+=](./operator+=/)(Callback) | Lägger till den angivna delegaten i samlingen. |
| [operator-=](./operator-=/)(Callback) | Tar bort den angivna delegaten från delegatsamlingen. |
| [operator=](./operator=/)(const MulticastDelegate\&) | Tilldelar delegatsamlingen som representeras av det angivna objektet till det aktuella objektet. Som resultat pekar båda objekten på samma delegatsamling. |
| [operator=](./operator=/)(MulticastDelegate\&&) | Flyttande tilldelningsoperator. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Avgör om delegatsamlingen är tom. |
| [operator==](./operator==/)(const MulticastDelegate\&) const | Bestämmer om två instanser av MulticastDelegate - det aktuella objektet och det angivna objektet - är lika. |
| [remove_empty_callbacks](./remove_empty_callbacks/)() const | Rensar bort inbäddade återuppringningar som är tomma (som faktiskt inte anropar något). |
| [ToString](./tostring/)() const |  |
| static [Type](./type/)() | Returnerar en referens till [TypeInfo](../typeinfo/)-objektet som representerar typinformationen för MulticastDelegate-klassen. |
| [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Callback](./callback/) | Typen av delegater som representeras av MulticastDelegate-klassen. |
| [Function](./function/) | Typen av funktionen relaterad till delegatsignaturen. |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
