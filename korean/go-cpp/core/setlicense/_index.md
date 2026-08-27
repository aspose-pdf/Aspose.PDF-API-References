---
title: "SetLicense"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "파일 이름으로 라이선스를 설정합니다."
type: docs
url: /ko/go-cpp/core/setlicense/
---

_파일 이름으로 라이선스를 설정합니다._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

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
	// SetLicense(filename string)는 파일 이름으로 라이선스를 설정합니다
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// PDF-document 작업하기
	// ...
}
```
