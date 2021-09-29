Results for repository - https://github.com/scoophealth/oscar.

## S1068
> Unused "private" fields should be removed. Link: https://rules.sonarsource.com/java/RSPEC-1068

Errors were thrown.
Link to repairs: [S1068.diff](/oscar/S1068.diff)


## S1118
> Utility classes should not have public constructors (incomplete: Only handles implicit public constructor). Link: https://rules.sonarsource.com/java/RSPEC-1118

UtilityClassWithPublicConstructorProcessor: 186
Link to repairs: [S1118.diff](/oscar/S1118.diff)


## S1132
> Strings literals should be placed on the left side when checking for equality. Link: https://rules.sonarsource.com/java/RSPEC-1132

Errors were thrown.
Link to repairs: [S1132.diff](/oscar/S1132.diff)


## S1155
> Collection.isEmpty() should be used to test for emptiness. Link: https://rules.sonarsource.com/java/RSPEC-1155

Errors were thrown.
Link to repairs: [S1155.diff](/oscar/S1155.diff)


## S1217
> "Thread.run()" should not be called directly. Link: https://rules.sonarsource.com/java/RSPEC-1217

No violations.
Link to repairs: [S1217.diff](/oscar/S1217.diff)


## S1444
> "public static" fields should be constant (incomplete: does not fix variable naming). Link: https://rules.sonarsource.com/java/RSPEC-1444

PublicStaticFieldShouldBeFinalProcessor: 278
Link to repairs: [S1444.diff](/oscar/S1444.diff)


## S1481
> Unused local variables should be removed. Link: https://rules.sonarsource.com/java/RSPEC-1481

Errors were thrown.
Link to repairs: [S1481.diff](/oscar/S1481.diff)


## S1596
> "Collections.EMPTY_LIST", "EMPTY_MAP", and "EMPTY_SET" should not be used. Link: https://rules.sonarsource.com/java/RSPEC-1596

CollectionsEmptyConstantsProcessor: 1
Link to repairs: [S1596.diff](/oscar/S1596.diff)


## S1656
> Variables should not be self-assigned. Link: https://rules.sonarsource.com/java/RSPEC-1656

No violations.
Link to repairs: [S1656.diff](/oscar/S1656.diff)


## S1854
> Unused assignments should be removed. Link: https://rules.sonarsource.com/java/RSPEC-1854

Errors were thrown.
Link to repairs: [S1854.diff](/oscar/S1854.diff)


## S1860
> Synchronization should not be based on Strings or boxed primitives. Link: https://rules.sonarsource.com/java/RSPEC-1860

No violations.
Link to repairs: [S1860.diff](/oscar/S1860.diff)


## S1948
> Fields in a "Serializable" class should either be transient or serializable. Link: https://rules.sonarsource.com/java/RSPEC-1948

SerializableFieldInSerializableClassProcessor: 26
Link to repairs: [S1948.diff](/oscar/S1948.diff)


## S2057
> Every class implementing Serializable should declare a static final serialVersionUID. (incomplete: This processor does not address the case where the class already has a serialVersionUID with a non long type.). Link: https://rules.sonarsource.com/java/RSPEC-2057

SerialVersionUidProcessor: 223
Link to repairs: [S2057.diff](/oscar/S2057.diff)


## S2095
> Resources should be closed. Link: https://rules.sonarsource.com/java/RSPEC-2095

UnclosedResourcesProcessor: 155
Link to repairs: [S2095.diff](/oscar/S2095.diff)


## S2097
> "equals(Object obj)" should test argument type. Link: https://rules.sonarsource.com/java/RSPEC-2097

EqualsArgumentTypeProcessor: 23
Link to repairs: [S2097.diff](/oscar/S2097.diff)


## S2111
> "BigDecimal(double)" should not be used. Link: https://rules.sonarsource.com/java/RSPEC-2111

BigDecimalDoubleConstructorProcessor: 58
Link to repairs: [S2111.diff](/oscar/S2111.diff)


## S2116
> "hashCode" and "toString" should not be called on array instances. Link: https://rules.sonarsource.com/java/RSPEC-2116

ArrayHashCodeAndToStringProcessor: 1
Link to repairs: [S2116.diff](/oscar/S2116.diff)


## S2142
> "InterruptedException" should not be ignored. Link: https://rules.sonarsource.com/java/RSPEC-2142

InterruptedExceptionProcessor: 6
Link to repairs: [S2142.diff](/oscar/S2142.diff)


## S2164
> Math should not be performed on floats. Link: https://rules.sonarsource.com/java/RSPEC-2164

MathOnFloatProcessor: 51
Link to repairs: [S2164.diff](/oscar/S2164.diff)


## S2167
> "compareTo" should not return "Integer.MIN_VALUE". Link: https://rules.sonarsource.com/java/RSPEC-2167

No violations.
Link to repairs: [S2167.diff](/oscar/S2167.diff)


## S2184
> Math operands should be cast before assignment. Link: https://rules.sonarsource.com/java/RSPEC-2184

CastArithmeticOperandProcessor: 19
Link to repairs: [S2184.diff](/oscar/S2184.diff)


## S2204
> ".equals()" should not be used to test the values of "Atomic" classes. Link: https://rules.sonarsource.com/java/RSPEC-2204

No violations.
Link to repairs: [S2204.diff](/oscar/S2204.diff)


## S2225
> "toString()" and "clone()" methods should not return null (incomplete: does not fix null returning clone()). Link: https://rules.sonarsource.com/java/RSPEC-2225

ToStringReturningNullProcessor: 0
Link to repairs: [S2225.diff](/oscar/S2225.diff)


## S2272
> "Iterator.next()" methods should throw "NoSuchElementException". Link: https://rules.sonarsource.com/java/RSPEC-2272

No violations.
Link to repairs: [S2272.diff](/oscar/S2272.diff)


## S2755
> XML parsers should not be vulnerable to XXE attacks (incomplete: This processor is a WIP and currently supports a subset of rule 2755. See Sorald's documentation for details.). Link: https://rules.sonarsource.com/java/RSPEC-2755

XxeProcessingProcessor: 40
Link to repairs: [S2755.diff](/oscar/S2755.diff)


## S3032
> JEE applications should not "getClassLoader". Link: https://rules.sonarsource.com/java/RSPEC-3032

GetClassLoaderProcessor: 29
Link to repairs: [S3032.diff](/oscar/S3032.diff)


## S3067
> "getClass" should not be used for synchronization. Link: https://rules.sonarsource.com/java/RSPEC-3067

No violations.
Link to repairs: [S3067.diff](/oscar/S3067.diff)


## S3984
> Exception should not be created without being thrown. Link: https://rules.sonarsource.com/java/RSPEC-3984

No violations.
Link to repairs: [S3984.diff](/oscar/S3984.diff)


## S4973
> Strings and Boxed types should be comparedusing "equals()". Link: https://rules.sonarsource.com/java/RSPEC-4973

CompareStringsBoxedTypesWithEqualsProcessor: 62
Link to repairs: [S4973.diff](/oscar/S4973.diff)


