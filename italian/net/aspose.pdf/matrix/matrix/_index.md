---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Costruttore della matrice. Il costruttore crea una matrice standard 1 a 1 A B C D E F 1 0 0 1 0 0.
type: docs
weight: 10
url: /it/net/aspose.pdf/matrix/matrix/
---
title: Matrice.Matrix  
second_title: Aspose.PDF for .NET Riferimento API  
description: Costruttore della matrice. Il costruttore crea una matrice standard 1x1 A B C D E F = [1, 0, 0, 1, 0, 0]  
type: docs  
weight: 10  
url: /net/aspose.pdf/matrix/matrix/  

## Matrice() {#constructor}  

Il costruttore crea una matrice standard 1x1: [ A B C D E F ] = [1, 0, 0, 1, 0, 0]  

```csharp
public Matrix()
```  
## Esempi  

```csharp
Matrix m = new Matrix();
```  
## Vedi anche  

* classe [Matrice](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)  

 | --- | --- |  
| matrixArray | Double[] | Array di dati della matrice. |  

## Esempi  

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```  
## Vedi anche  

* classe [Matrice](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)  

---  

## Matrice(float[]) {#constructor_4}  

Il costruttore accetta una matrice con la seguente rappresentazione array: [ A B C D E F ]  

```csharp
public Matrix(float[] matrixArray)
```  
| Parametro | Tipo | Descrizione |  
| --- | --- | --- |  
| matrixArray | Single[] | Array di dati della matrice. |  

### Vedi anche  

* classe [Matrice](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)  

---  

## Matrice(Matrice) {#constructor_1}  

Il costruttore accetta una matrice per creare una copia.  

```csharp
public Matrix(Matrix matrix)
```  
| Parametro | Tipo | Descrizione |  
| --- | --- | --- |  
| matrix | Matrice | Oggetto della matrice. |  

### Vedi anche  

* classe [Matrice](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)  

---  

## Matrice(double, double, double, double, double, double) {#constructor_2}  

Inizializza la matrice di trasformazione con i coefficienti specificati.  

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```  
| Parametro | Tipo | Descrizione |  
| --- | --- | --- |  
| a | Double | Valore A della matrice. |  
| b | Double | Valore B della matrice. |  
| c | Double | Valore C della matrice. |  
| d | Double | Valore D della matrice. |  
| e | Double | Valore E della matrice. |  
| f | Double | Valore F della matrice. |  

## Esempi  

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```  
## Vedi anche  

* classe [Matrice](../)  
* namespace [Aspose.Pdf](../../../aspose.pdf/)  
* assembly [Aspose.PDF](../../../)