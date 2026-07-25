---
title: "ExportFdf"
second_title: "Aspose.PDF for Go via C++"
description: "AcroForm içeren önceden açılmış PDF-dokümanını FDF-dokümanına dışa aktar."
type: docs
url: /tr/go-cpp/convert/exportfdf/
---

_AcroForm ile daha önce açılmış PDF-dokümandan FDF-dokümana dışa aktar._

```go
func (document *Document) ExportFdf(filename string) error
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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// ExportFdf(filename string) AcroForm ile daha önce açılmış PDF-dokümandan FDF-dokümana dosya adıyla dışa aktarır
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
