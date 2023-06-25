# POCO-Generator
SQL Server .NET Object Generator

POCO-Generator
POCO Generator https://www.codeproject.com/Articles/892233/POCO-Generator

# POCO
The POCO section manages the structure of the POCO.

- Properties/Data Members - Normally, a POCO is constructed with properties, but this option gives an option to use data members instead.
- Virtual Properties - Adds a virtual modifier to the properties.
- Override Properties - Adds an override modifier to the properties.
- Partial Class - Adds a partial modifier to the class.
- Struct Types Nullable - All the struct types will become nullable (int?, DateTime?) even if they are not nullable in the database.
- Comments & Without null - A comment, for each property, of the original SQL Server type and whether it is nullable. Without null removes the nullable comments.
- using - Adds using statements at the beginning of the POCO.
- Namespace - Wraps the POCO with the specified namespace.
- Inherit - Adds a comma-delimited list of inherit base class and interfaces.
- Column Defaults - Adds properties initialization, based on the column default values in SQL Server. Default value that can't be handled properly will be commented.
- New Line Between Members - If the POCOs become larger, especially with EF annotations, this option will add lines between the POCO properties.

## Screenshot

Login </br>
![Login](https://github.com/EnterpriseSolution/POCO-Generator/blob/master/Login.jpg)

Generator </br>
![Generator](https://github.com/EnterpriseSolution/POCO-Generator/blob/master/Generator.jpg)

## Dependency

* .NET Framework 4.0
