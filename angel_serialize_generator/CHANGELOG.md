# 2.0.6
* Support for using `abstract` to create immutable model classes.

# 2.0.5
* Deserialization now supports un-serialized `DateTime`.
* Better support for regular typed Lists and Maps in TypeScript.

# 2.0.4
* Fields in TypeScript definitions are now nullable by default.

# 2.0.3
* Added a `TypeScriptDefinitionBuilder`.

# 2.0.2
* Generates an `XFields` class with the serialized names of
all fields in a model class `X`.
* Removed unnecessary named parameters from `XSerializer.fromMap`.

# 2.0.1
* Ensured that `List` is only transformed if
it generically references a `Model`.