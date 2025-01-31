# 特征（Traits）

Rust 类型系统的第二个核心支柱是特征（`traits`）的使用，它允许编码在不同类型之间通用的行为。特征在其他语言中大致等同于接口类型，但它们也与 Rust 的泛型（[第 12 条]）相关联，允许在不产生运行时开销的情况下重用接口。

本章中的条目描述了 Rust 编译器和 Rust 工具链提供的标准特征，并提供了关于如何设计和使用特征编码行为的建议。


<!-- 参考链接 -->

[第 12 条]: ../chapter_2/item12-generics&trait-objects.md
