---
title: "ExportFdf"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "AcroForm이 포함된 이전에 열었던 PDF-document를 FDF-document로 내보냅니다."
type: docs
url: /ko/go-cpp/convert/exportfdf/
---

_AcroForm이 포함된 이전에 열려 있던 PDF-문서에서 FDF-문서로 내보냅니다._

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
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// ExportFdf(filename string) AcroForm이 포함된 이전에 열려 있던 PDF-문서를 파일 이름을 지정하여 FDF-문서로 내보냅니다
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
