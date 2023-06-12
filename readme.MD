# Rust JSON Reader

This Rust project is a simple JSON parser that reads and displays content from a predefined JSON string representing an article. Each article is composed of a title, an author, and a list of paragraphs. The content of a paragraph is then displayed to the user.

The JSON structure is converted into Rust data structures (structs) for easy manipulation and access. The **serde crate** is used for _serialization_ and _deserialization_ between Rust structs and JSON data.

**Note:** Please keep in mind that the program currently does not handle out-of-bound accesses. Trying to access an index that is out of bounds in the paragraph vector will cause the program to panic.

## Running

command:
```cargo run```