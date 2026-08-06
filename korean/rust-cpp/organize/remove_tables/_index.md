---
title: "remove_tables"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document에서 테이블을 제거합니다."
type: docs
url: /ko/rust-cpp/organize/remove_tables/
---

_PDF-document에서 테이블을 제거합니다._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document에서 테이블을 제거합니다
    pdf.remove_tables()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```