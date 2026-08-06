---
title: "save_tiff"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다."
type: docs
url: /ko/rust-cpp/convert/save_tiff/
---

_이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **resolution_dpi** - the resolution in DPI
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

    // 이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```