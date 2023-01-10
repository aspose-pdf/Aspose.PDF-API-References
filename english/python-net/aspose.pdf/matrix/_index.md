---
title: Matrix
second_title: Aspose.PDF for Python via .NET API Reference
description: Class represents transformation matrix.
type: docs
weight: 900
url: /python-net/aspose.pdf/matrix/
---

## Matrix class

Class represents transformation matrix.

The Matrix type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Matrix()|Constructor<br/>            creates stanrard 1 to 1 matrix:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]|
|Matrix(matrix_array)|Initializes a new instance of the Matrix class|
|Matrix(matrix_array)|Initializes a new instance of the Matrix class|
|Matrix(matrix)|Initializes a new instance of the Matrix class|
|Matrix(a, b, c, d, e, f)|Initializes a new instance of the Matrix class|
## Properties
| Name | Description |
| :- | :- |
|data|Gets data of Matrix as array.|
|a|A member of the transformation matrix.|
|b|B member of the transformation matrix.|
|c|C member of the transformation matrix.|
|d|D member of the transformation matrix.|
|e|E member of the transformation matrix.|
|f|F member of the transformation matrix.|
|elements|Elements of the matrix.|
## Methods
| Name | Description |
| :- | :- |
|rotation(alpha)|Creates matrix for given rotation angle.|
|rotation(rotation)|Creates matrix for given rotation angle.|
|transform(p)|Transforms point using this matrix.|
|transform(rect)|Transformes rectangle.<br/>            If angle is not 90 * N degrees then bounding rectangle is returned.|
|skew(alpha, beta)|Creates matrix for given rotation angle.|
|get_angle(rotation)|Transaltes rotation into angle (degrees)|
|multiply(other)|Multiplies the matrix by other matrix.|
|add(other)|Adds matrix to other matrix.|
|reverse()|Calculates reverse matrix.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

