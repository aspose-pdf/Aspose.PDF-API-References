---
title: "GetMetaInfo"
second_title: "Aspose.PDF para Go vía C++"
description: "Obtiene el valor de la información meta del documento PDF."
type: docs
url: /es/go-cpp/core/getmetainfo/
---

_Obtiene el valor de la información meta del documento PDF._

```go
func (document *Document) GetMetaInfo(key string) (string, error)
```

**Parameters**: 
  * **key** - key whose value to get

**Return**: 
  * **string** - value associated with the specified key
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// GetMetaInfo(key string) obtiene el valor de la información meta del documento PDF
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Author: ", value)
}
```
