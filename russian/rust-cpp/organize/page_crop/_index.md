---
title: "page_crop"
second_title: "Aspose.PDF для Rust через C++"
description: "Обрезает страницу."
type: docs
url: /ru/rust-cpp/organize/page_crop/
---

_Обрезает страницу._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Обрезать страницу
    pdf.page_crop(1, 1.0)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```