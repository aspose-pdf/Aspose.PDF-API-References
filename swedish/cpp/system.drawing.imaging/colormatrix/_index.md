---
title: "System::Drawing::Imaging::ColorMatrix class"
linktitle: "ColorMatrix"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::ColorMatrix class. Representerar en 5x5-matris som innehåller koordinaterna för RGBAW-färgrymden. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.drawing.imaging/colormatrix/
---
## ColorMatrix class


Representerar en 5x5-matris som innehåller koordinaterna för RGBAW-färgrymden. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ColorMatrix : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ColorMatrix](./colormatrix/)() | Skapar en ny instans av [ColorMatrix](./) klass och initierar den med värdena från identitetsmatrisen. |
| [ColorMatrix](./colormatrix/)(const System::ArrayPtr\<System::ArrayPtr\<float\>\>\&) | Skapar en ny instans av [ColorMatrix](./) klass och initierar den med de angivna värdena. |
| [get_Matrix00](./get_matrix00/)() const | Returnerar ett värde i 0:e raden och 0:e kolumnen. |
| [get_Matrix01](./get_matrix01/)() const | Returnerar ett värde i 0:e raden och 1:a kolumnen. |
| [get_Matrix02](./get_matrix02/)() const | Returnerar ett värde i 0:e raden och 2:a kolumnen. |
| [get_Matrix03](./get_matrix03/)() const | Returnerar ett värde i 0:e raden och 3:e kolumnen. |
| [get_Matrix04](./get_matrix04/)() const | Returnerar ett värde i 0:e raden och 4:e kolumnen. |
| [get_Matrix10](./get_matrix10/)() const | Returnerar ett värde i 1:a raden och 0:e kolumnen. |
| [get_Matrix11](./get_matrix11/)() const | Returnerar ett värde i 1:a raden och 1:a kolumnen. |
| [get_Matrix12](./get_matrix12/)() const | Returnerar ett värde i 1:a raden och 2:a kolumnen. |
| [get_Matrix13](./get_matrix13/)() const | Returnerar ett värde i 1:a raden och 3:e kolumnen. |
| [get_Matrix14](./get_matrix14/)() const | Returnerar ett värde i 1:a raden och 4:e kolumnen. |
| [get_Matrix20](./get_matrix20/)() const | Returnerar ett värde i 2:a raden och 0:e kolumnen. |
| [get_Matrix21](./get_matrix21/)() const | Returnerar ett värde i 2:a raden och 1:a kolumnen. |
| [get_Matrix22](./get_matrix22/)() const | Returnerar ett värde i 2:a raden och 2:a kolumnen. |
| [get_Matrix23](./get_matrix23/)() const | Returnerar ett värde i 2:a raden och 3:e kolumnen. |
| [get_Matrix24](./get_matrix24/)() const | Returnerar ett värde i 2:a raden och 4:e kolumnen. |
| [get_Matrix30](./get_matrix30/)() const | Returnerar ett värde i 3:e raden och 0:e kolumnen. |
| [get_Matrix31](./get_matrix31/)() const | Returnerar ett värde i 3:e raden och 1:a kolumnen. |
| [get_Matrix32](./get_matrix32/)() const | Returnerar ett värde i 3:e raden och 2:a kolumnen. |
| [get_Matrix33](./get_matrix33/)() const | Returnerar ett värde i 3:e raden och 3:e kolumnen. |
| [get_Matrix34](./get_matrix34/)() const | Returnerar ett värde i 3:e raden och 4:e kolumnen. |
| [get_Matrix40](./get_matrix40/)() const | Returnerar ett värde i 4:e raden och 0:e kolumnen. |
| [get_Matrix41](./get_matrix41/)() const | Returnerar ett värde i 4:e raden och 1:a kolumnen. |
| [get_Matrix42](./get_matrix42/)() const | Returnerar ett värde i 4:e raden och 2:a kolumnen. |
| [get_Matrix43](./get_matrix43/)() const | Returnerar ett värde i 4:e raden och 3:e kolumnen. |
| [get_Matrix44](./get_matrix44/)() const | Returnerar ett värde i 4:e raden och 4:e kolumnen. |
| [idx_get](./idx_get/)(int, int) | Returnerar ett värde på den angivna raden och kolumnen. |
| [idx_set](./idx_set/)(int, int, float) | Sätter det specificerade värdet på den angivna platsen i matrisen. |
| [set_Matrix00](./set_matrix00/)(float) | Sätter ett värde i 0:e raden och 0:e kolumnen. |
| [set_Matrix01](./set_matrix01/)(float) | Sätter ett värde i 0:e raden och 1:a kolumnen. |
| [set_Matrix02](./set_matrix02/)(float) | Sätter ett värde i 0:e raden och 2:a kolumnen. |
| [set_Matrix03](./set_matrix03/)(float) | Sätter ett värde i 0:e raden och 3:e kolumnen. |
| [set_Matrix04](./set_matrix04/)(float) | Sätter ett värde i 0:e raden och 4:e kolumnen. |
| [set_Matrix10](./set_matrix10/)(float) | Sätter ett värde i 1:a raden och 0:e kolumnen. |
| [set_Matrix11](./set_matrix11/)(float) | Sätter ett värde i 1:a raden och 1:a kolumnen. |
| [set_Matrix12](./set_matrix12/)(float) | Sätter ett värde i 1:a raden och 2:a kolumnen. |
| [set_Matrix13](./set_matrix13/)(float) | Sätter ett värde i den 1:a raden och 3:e kolumnen. |
| [set_Matrix14](./set_matrix14/)(float) | Sätter ett värde i den 1:a raden och 4:e kolumnen. |
| [set_Matrix20](./set_matrix20/)(float) | Sätter ett värde i den 2:a raden och 0:e kolumnen. |
| [set_Matrix21](./set_matrix21/)(float) | Sätter ett värde i den 2:a raden och 1:e kolumnen. |
| [set_Matrix22](./set_matrix22/)(float) | Sätter ett värde i den 2:a raden och 2:e kolumnen. |
| [set_Matrix23](./set_matrix23/)(float) | Sätter ett värde i den 2:a raden och 3:e kolumnen. |
| [set_Matrix24](./set_matrix24/)(float) | Sätter ett värde i den 2:a raden och 4:e kolumnen. |
| [set_Matrix30](./set_matrix30/)(float) | Sätter ett värde i den 3:e raden och 0:e kolumnen. |
| [set_Matrix31](./set_matrix31/)(float) | Sätter ett värde i den 3:e raden och 1:e kolumnen. |
| [set_Matrix32](./set_matrix32/)(float) | Sätter ett värde i den 3:e raden och 2:e kolumnen. |
| [set_Matrix33](./set_matrix33/)(float) | Sätter ett värde i den 3:e raden och 3:e kolumnen. |
| [set_Matrix34](./set_matrix34/)(float) | Sätter ett värde i den 3:e raden och 4:e kolumnen. |
| [set_Matrix40](./set_matrix40/)(float) | Sätter ett värde i den 4:e raden och 0:e kolumnen. |
| [set_Matrix41](./set_matrix41/)(float) | Sätter ett värde i den 4:e raden och 1:e kolumnen. |
| [set_Matrix42](./set_matrix42/)(float) | Sätter ett värde i den 4:e raden och 2:e kolumnen. |
| [set_Matrix43](./set_matrix43/)(float) | Sätter ett värde i den 4:e raden och 3:e kolumnen. |
| [set_Matrix44](./set_matrix44/)(float) | Sätter ett värde i den 4:e raden och 4:e kolumnen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
