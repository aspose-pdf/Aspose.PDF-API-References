---
title: "OptimizeFileSize"
second_title: "Aspose.PDF para Go via C++"
description: "Otimizar o tamanho do documento PDF com qualidade de compressão de imagem."
type: docs
url: /pt/go-cpp/organize/optimizefilesize/
---

_Otimize o tamanho do PDF-document com qualidade de compressão de imagem._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) otimiza o tamanho do PDF-document com qualidade de compressão de imagem
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
