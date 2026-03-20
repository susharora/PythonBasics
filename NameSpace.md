## What is namespace ?
Namespace is actual mapping between names and objects and is implemented as a dictionary. 
- Objects are kept in Object space.
- There is a reference from namespace to object. 
- Function names are also a name and object pair
## what happens when we change value of a number or a string varibale?
The namespace now references another new object in memory since string/number cannot be altered. The unreferenced string object is then deleted by garbage collection module which is not managed by programmer. 


