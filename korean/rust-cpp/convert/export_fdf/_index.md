---
title: "export_fdf"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "AcroForm이 포함된 이전에 연 PDF 문서를 파일 이름이 있는 FDF 문서로 내보냅니다."
type: docs
url: /ko/rust-cpp/convert/export_fdf/
---

_AcroForm이 포함된 이전에 연 PDF 문서를 파일 이름이 있는 FDF 문서로 내보냅니다._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // AcroForm이 포함된 이전에 연 PDF 문서를 FDF 문서로 내보냅니다
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```