---
title: "split_at"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقسم مستند PDF-document الحالي إلى مستندين PDF-documents جديدين."
type: docs
url: /ar/rust-cpp/core/split_at/
---

_يقسم مستند PDF-document الحالي إلى مستندين PDF-documents جديدين._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // قسم مستند PDF-document الحالي إلى مستندين PDF-documents جديدين
    let (left, right) = pdf_split.split_at(2)?;

    // احفظ كل جزء مقسّم كملف PDF-document منفصل
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```