# cs-scala-crosscompile-sample

A basic sample on how to use Scala 2.11, 2.12 and 2.13 in the same project

Use it with:

`+run`

NOTE: Obviously this is just a hello world, but the idea for real project is to have most of the code at src/main/scala and
put only the incompatible code under scala-2.11, scala-2.12 and scala-2.13 (it's a good idea tu use traits to use
this differences in a generic way at the main scala code)
