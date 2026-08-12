---
title: "IsLinearized"
second_title: "Aspose.PDF for Go via C++"
description: "Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer al."
type: docs
url: /tr/go-cpp/core/islinearized/
---

_Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer al._

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// IsLinearized() belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer alır
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
