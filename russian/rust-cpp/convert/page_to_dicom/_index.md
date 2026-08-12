---
title: "page_to_dicom"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует и сохраняет указанную страницу как DICOM‑изображение."
type: docs
url: /ru/rust-cpp/convert/page_to_dicom/
---

_Преобразует и сохраняет указанную страницу как DICOM‑изображение._

```rust
pub fn page_to_dicom(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
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

    // Преобразовать и сохранить указанную страницу как DICOM‑изображение
    pdf.page_to_dicom(1, 100, "sample_page1.dcm")?;

    Ok(())
}

```