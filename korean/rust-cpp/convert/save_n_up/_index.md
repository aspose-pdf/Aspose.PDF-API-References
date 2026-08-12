---
title: "save_n_up"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열어둔 PDF 문서를 N-Up PDF 문서로 변환하고 저장합니다."
type: docs
url: /ko/rust-cpp/convert/save_n_up/
---

_이전에 열어둔 PDF 문서를 N-Up PDF 문서로 변환하고 저장합니다._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이전에 열어둔 PDF 문서를 N-Up PDF 문서로 변환하고 저장합니다
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```