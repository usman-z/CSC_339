# Chapter 5 - Names, Scopes, and Bindings

## Section 5.2
__Keywords:__ Used by the Language  
__Reserved words:__ Words not allowed to be Identifiers  

__Note:__ PL/1 and Algol don't have reserve words  

## Section 5.3 
__Variables:__ Entities with a set of attributes

Typical attributes of a Variable:
-  Type
-  Name
-  Value
-  Address
-  Duration/Lifetime
-  Scope

__More about Address("left-value"):__ 
-  can change dynamically
-  can have multiple instances of a var, with different addresses (Think recursive function's call stack)
-  can have one address with multiple variables with different names (aka Aliasing)
-  When does a Variable get an address? At Binding time  

__More about Values("right-value"):__ 
-  actual contents of the memory holder/cell

__Binding:__ Association between _entity_ and _attribute_  
&nbsp;&nbsp;&nbsp;&nbsp;__Static Binding:__  Before Execution/Run time, Determined/Bound at Compile or Link time  
&nbsp;&nbsp;&nbsp;&nbsp;__Dynamic Binding:__ During Execution, Bound at Run time


