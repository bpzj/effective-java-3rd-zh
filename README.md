# 介绍(Introduce)
- 个人翻译

# 目录(Contents)

## **Chapter 1. Introduction (引言)**

## **Chapter 2. Creating and Destroying Objects (创建和销毁对象)**
- [Chapter 2 Introduction](2.Creating-and-Destroying-Objects/2.0-Introduction.md)
- [Item 1: Consider static factory methods instead of constructors
  (考虑使用静态工厂方法，而不是构造函数) ](2.Creating-and-Destroying-Objects/2.1-static-factory-methods.md)
- [Item 2: Consider a builder when faced with many constructor parameters
  (可选参数过多导致过多构造函数时,考虑builder)](2.Creating-and-Destroying-Objects/2.2-builder.md)
- Item 3: Enforce the singleton property with a private constructor or an enum type
- Item 4: Enforce noninstantiability with a private constructor
- Item 5: Prefer dependency injection to hardwiring resources
- Item 6: Avoid creating unnecessary objects
- Item 7: Eliminate obsolete object references
- Item 8: Avoid finalizers and cleaners
- Item 9: Prefer try-with-resources to try-finally

## **3. Methods Common to All Objects**
- Item 10: Obey the general contract when overriding equals
- Item 11: Always override hashCode when you override equals
- Item 12: Always override toString  
- Item 13: Override clone judiciously
- Item 14: Consider implementing Comparable

## **4. Classes and Interfaces**
- Item 15: Minimize the accessibility of classes and members 
- Item 16: In public classes, use accessor methods, not public fields
- Item 17: Minimize mutability
- Item 18: Favor composition over inheritance
- Item 19: Design and document for inheritance or else prohibit it
- Item 20: Prefer interfaces to abstract classes
- Item 21: Design interfaces for posterity
- Item 22: Use interfaces only to define types
- Item 23: Prefer class hierarchies to tagged classes
- Item 24: Favor static member classes over nonstatic
- Item 25: Limit source files to a single top-level class

## **5. Generics**
- Item 26: Don’t use raw types
- Item 27: Eliminate unchecked warnings
- Item 28: Prefer lists to arrays
- Item 29: Favor generic types
- Item 30: Favor generic methods
- Item 31: Use bounded wildcards to increase API flexibility
- Item 32: Combine generics and varargs judiciously
- Item 33: Consider typesafe heterogeneous containers

## **6 Enums and Annotations**
- Item 34: Use enums instead of int constants
- Item 35: Use instance fields instead of ordinals
- Item 36: Use EnumSet instead of bit fields 
- Item 37: Use EnumMap instead of ordinal indexing
- Item 38: Emulate extensible enums with interfaces
- Item 39: Prefer annotations to naming patterns 
- Item 40: Consistently use the Override annotation
- Item 41: Use marker interfaces to define types

## **7 Lambdas and Streams**
- Item 42: Prefer lambdas to anonymous classes
- Item 43: Prefer method references to lambdas
- Item 44: Favor the use of standard functional interfaces
- Item 45: Use streams judiciously
- Item 46: Prefer side-effect-free functions in streams
- Item 47: Prefer Collection to Stream as a return type
- Item 48: Use caution when making streams parallel

## **8 Methods**
- Item 49: Check parameters for validity
  [(检查参数的有效性)](8.Methods/8.49-Check-parameters-for-validity.md)
- Item 50: Make defensive copies when needed
  [(在需要时制作防御性副本)](8.Methods/8.50-Make-defensive-copies-when-needed.md)
- Item 51: Design method signatures carefully
  [(仔细设计方法签名)](8.Methods/8.51-Design-method-signatures-carefully.md)
- Item 52: Use overloading judiciously
  [(明智地使用重载)](8.Methods/8.52-Use-overloading-judiciously.md)
- Item 53: Use varargs judiciously
  [(明智地使用可变参数)](8.Methods/8.53-Use-varargs-judiciously.md)
- Item 54: Return empty collections or arrays, not nulls
  [(返回空集合或数组，而不是 null)](8.Methods/8.54-Return-empty-collections-or-arrays-not-nulls.md)
- Item 55: Return optionals judiciously
  [(明智地的返回 Optional)](8.Methods/8.55-Return-optionals-judiciously.md)
- Item 56: Write doc comments for all exposed API elements
  [(为所有公开的 API 元素编写文档注释)](8.Methods/8.56-Write-doc-comments-for-all-exposed-API-elements.md)

## **9 General Programming**
- Item 57: Minimize the scope of local variables
- Item 58: Prefer for-each loops to traditional for loops
- Item 59: Know and use the libraries
- Item 60: Avoid float and double if exact answers are required
- Item 61: Prefer primitive types to boxed primitives
- Item 62: Avoid strings where other types are more appropriate 
- Item 63: Beware the performance of string concatenation
- Item 64: Refer to objects by their interfaces
- Item 65: Prefer interfaces to reflection 
- Item 66: Use native methods judiciously
- Item 67: Optimize judiciously
- Item 68: Adhere to generally accepted naming conventions

## **10. Exceptions**
- Item 69: Use exceptions only for exceptional conditions
- Item 70: Use checked exceptions for recoverable conditions and runtime exceptions for programming errors 
- Item 71: Avoid unnecessary use of checked exceptions
- Item 72: Favor the use of standard exceptions
- Item 73: Throw exceptions appropriate to the abstraction
- Item 74: Document all exceptions thrown by each method
- Item 75: Include failure-capture information in detail messages
- Item 76: Strive for failure atomicity
- Item 77: Don’t ignore exceptions

## **11. Concurrency**
- Item 78: Synchronize access to shared mutable data
- Item 79: Avoid excessive synchronization
- Item 80: Prefer executors, tasks, and streams to threads
- Item 81: Prefer concurrency utilities to wait and notify
- Item 82: Document thread safety
- Item 83: Use lazy initialization judiciously
- Item 84: Don’t depend on the thread scheduler

## **12. Serialization**
- Item 85: Prefer alternatives to Java serialization 
- Item 86: Implement Serializable with great caution 
- Item 87: Consider using a custom serialized form 
- Item 88: Write readObject methods defensively 
- Item 89: For instance control, prefer enum types to readResolve
- Item 90: Consider serialization proxies instead of serialized instances
## Items Corresponding to Second Edition
## References
## Index


## 联系(Contact)

- Email：`1521189886@qq.com`

