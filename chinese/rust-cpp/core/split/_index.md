---
title: "split"
second_title: "Aspose.PDF for Rust via C++"
description: "通过从当前 PDF 文档提取页面来创建多个新 PDF 文档。"
type: docs
url: /zh/rust-cpp/core/split/
---

_通过从当前 PDF 文档提取页面来创建多个新 PDF 文档。_

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf_split = Document::open("sample.pdf")?;

    // 通过从当前 PDF 文档提取页面来创建多个新 PDF 文档
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // 将每个拆分部分保存为单独的 PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```