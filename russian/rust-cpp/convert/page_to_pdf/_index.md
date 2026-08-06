---
title: "page_to_pdf"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует и сохраняет указанную страницу как PDF‑документ."
type: docs
url: /ru/rust-cpp/convert/page_to_pdf/
---

_Преобразует и сохраняет указанную страницу как PDF‑документ._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Преобразовать и сохранить указанную страницу как PDF‑документ
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```