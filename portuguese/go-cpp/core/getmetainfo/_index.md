---
title: "GetMetaInfo"
second_title: "Aspose.PDF para Go via C++"
description: "Obter o valor da informação meta do PDF-document."
type: docs
url: /pt/go-cpp/core/getmetainfo/
---

_Obter o valor da informação meta do PDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// GetMetaInfo(key string) obtém o valor da informação meta do PDF-document
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Author: ", value)
}
```
