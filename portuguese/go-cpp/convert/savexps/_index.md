---
title: "SaveXps"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento Xps."
type: docs
url: /pt/go-cpp/convert/savexps/
---

_Converta e salve o documento PDF previamente aberto como documento Xps._

```go
func (document *Document) SaveXps(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// SaveXps(filename string) salva o documento PDF previamente aberto como documento Xps com o nome de arquivo
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
