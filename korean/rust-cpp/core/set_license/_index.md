---
title: "set_license"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "파일 이름을 사용하여 라이선스를 설정합니다."
type: docs
url: /ko/rust-cpp/core/set_license/
---

_파일 이름을 사용하여 라이선스를 설정합니다._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 파일 이름으로 라이선스를 설정
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // 이제 라이선스가 있는 PDF 문서를 작업할 수 있습니다
    // ...

    Ok(())
}

```