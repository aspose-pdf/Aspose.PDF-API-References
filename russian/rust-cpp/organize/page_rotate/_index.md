---
title: "page_rotate"
second_title: "Aspose.PDF для Rust через C++"
description: "Поворачивает страницу в PDF-document."
type: docs
url: /ru/rust-cpp/organize/page_rotate/
---

_Поворачивает страницу в PDF-document._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Повернуть страницу
    pdf.page_rotate(1, Rotation::On180)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```