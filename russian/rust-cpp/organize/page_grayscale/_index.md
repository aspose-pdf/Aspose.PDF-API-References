---
title: "page_grayscale"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует страницу в черно-белый режим."
type: docs
url: /ru/rust-cpp/organize/page_grayscale/
---

_Преобразует страницу в черно-белый режим._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Преобразовать страницу в черно-белый режим
    pdf.page_grayscale(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```