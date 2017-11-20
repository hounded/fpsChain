## Primitive types

Composer resources are defined in terms of the following primitive types:
* String: a UTF8 encoded String.
* Double: a double precision 64 bit numeric value.
* Integer: a 32 bit signed whole number.
* Long: a 64 bit signed whole number.
* DateTime: an ISO-8601 compatible time instance, with optional time zone and UTZ offset.
* Boolean: a Boolean value, either true or false.

## Arrays

All types in Composer may be declared as arrays using the [] notation.
Copy
```hyperledger
Integer[] integerArray
```
Is an array of Integers stored in a field called 'integerArray'. While
Copy
```hyperledger
--> Animal[] incoming
```
Is an array of relationships to the Animal type, stored in a field called 'incoming'.