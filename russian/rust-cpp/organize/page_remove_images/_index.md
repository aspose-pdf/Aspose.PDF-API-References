---
title: "page_remove_images"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет изображения на странице."
type: docs
url: /ru/rust-cpp/organize/page_remove_images/
---

_Удаляет изображения на странице._

```rust
pub fn page_remove_images(&self, num: i32) -> Result<(), PdfError>
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

    // Удалить изображения на странице
    pdf.page_remove_images(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_remove_images.pdf")?;

    Ok(())
}

```