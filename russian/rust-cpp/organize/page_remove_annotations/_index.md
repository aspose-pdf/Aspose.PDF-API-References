---
title: "page_remove_annotations"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет аннотации на странице."
type: docs
url: /ru/rust-cpp/organize/page_remove_annotations/
---

_Удаляет аннотации на странице._

```rust
pub fn page_remove_annotations(&self, num: i32) -> Result<(), PdfError>
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

    // Удалить аннотации на странице
    pdf.page_remove_annotations(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_remove_annotations.pdf")?;

    Ok(())
}

```