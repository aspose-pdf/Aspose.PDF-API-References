---
title: "System::Text::RegularExpressions namnrymd"
linktitle: "System::Text::RegularExpressions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Text::RegularExpressions namnrymd i C++."
type: docs
weight: 7100
url: /sv/cpp/system.text.regularexpressions/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Capture](./capture/) | Resultat av matchning av en enda deluttryck. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [CaptureCollection](./capturecollection/) | Lista över fångster gjorda av en enda fångstgrupp. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Group](./group/) | Resultat av matchning utförd av en enda fångstgrupp. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [GroupCollection](./groupcollection/) | Lista över fångstgrupper i en enda matchning. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) samlingspekare. Denna typ är en pekare för att hantera radering av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [Match](./match/) | [Single](../system/single/) matchning av reguljärt uttryck mot en sträng. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MatchCollection](./matchcollection/) | Samling av matchningar gjorda genom att upprepade gånger tillämpa reguljärt uttryck på en sträng. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Regex](./regex/) | Reguljärt uttryck som följer C#-lik syntax. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) alternativ. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pekare till fångstsamling. |
| [CapturePtr](./captureptr/) | Pekare till enskilt fångstobjekt. |
| [GroupPtr](./groupptr/) | Pekare till grupp. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) samlingspekare. |
| [MatchEvaluator](./matchevaluator/) | Delegattyp för att utvärdera matchning. |
| [MatchPtr](./matchptr/) | [Match](./match/) pekare. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pekare. |
| [UStringPtr](./ustringptr/) | Delad UnicodeString för att undvika kopiering. |
