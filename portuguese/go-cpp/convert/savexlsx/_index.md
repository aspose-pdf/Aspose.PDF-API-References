---
title: "SaveXlsX"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento XlsX."
type: docs
url: /pt/go-cpp/convert/savexlsx/
---

_Converta e salve o documento PDF previamente aberto como documento XlsX._

```go
func (document *Document) SaveXlsX(filename string) error
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
	// SaveXlsX(filename string) salva o documento PDF previamente aberto como documento XlsX com o nome de arquivo
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
}
```
