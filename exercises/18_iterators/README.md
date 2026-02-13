# Iterators

This section will teach you about Iterators.

## Further information

- [Iterator](https://doc.rust-lang.org/book/ch13-02-iterators.html)
- [Iterator documentation](https://doc.rust-lang.org/stable/std/iter/)


| Method | What it does | Ownership Level |
| :--- | :--- | :--- |
| `iter()` | Iterates over **immutable references** (`&T`). | You just want to look at the data. |
| `iter_mut()` | Iterates over **mutable references** (`&mut T`). | You want to change the data in place. |
| `into_iter()` | **Consumes** the collection and returns values (`T`). | The collection is moved; you can't use it afterward. |
