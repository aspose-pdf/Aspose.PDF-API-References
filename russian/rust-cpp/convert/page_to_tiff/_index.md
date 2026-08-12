---
title: "page_to_tiff"
second_title: "Aspose.PDF для Rust через C++"
description: "Конвертирует и сохраняет указанную страницу как TIFF‑изображение."
type: docs
url: /ru/rust-cpp/convert/page_to_tiff/
---

_Конвертирует и сохраняет указанную страницу как TIFF‑изображение._

```rust
pub fn page_to_tiff(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **resolution_dpi** - the resolution in DPI
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

    // Конвертировать и сохранить указанную страницу как Tiff‑изображение
    pdf.page_to_tiff(1, 100, "sample_page1.tiff")?;

    Ok(())
}

```