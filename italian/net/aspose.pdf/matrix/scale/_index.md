---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Metodo matrice. Modifica le scale x e y con la matrice utilizzando il seguente formula x1 A x C y y1 B x D y
type: docs
weight: 190
url: /it/net/aspose.pdf/matrix/scale/
---
title: Matrix.Scale  
second_title: API Reference Aspose.PDF for .NET  
description: Scala x e y con la matrice utilizzando la seguente formula x1 = A*x + C*y; y1 = B*x + D*y;  
type: docs  
weight: 190  
url: /net/aspose.pdf/matrix/scale/  

## Scale(double, double, out double, out double)  

Scala x e y con la matrice utilizzando la seguente formula:  
x1 = A*x + C*y;  
y1 = B*x + D*y;  

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```  

| Parametro | Tipo | Descrizione |  
| --- | --- | --- |  
| x | Double | Coordinato X di input |  
| y | Double | Coordinato Y di input |  
| x1 | Double& | Coordinato X di output |  
| y1 | Double& | Coordinato Y di output |  

### Vedi anche  

* classe [Matrix](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)  

 | --- | --- |  
| sx | Double | Fattore di scalatura per l'asse X |  
| sy | Double | Fattore di scalatura per l'asse Y |  
| source | Matrix | Matrice da scalare |  

### Valore di ritorno  

Matrice nuova che è il risultato della scalatura della matrice source.  

### Vedi anche  

* classe [Matrix](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)