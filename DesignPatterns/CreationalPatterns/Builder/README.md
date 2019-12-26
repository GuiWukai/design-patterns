## Motivation

- Some objects are simple and can be created in a single constructor call
- Other objects require a lot of ceremony to create
- Having an abject with object with 10 cosntructor arguments is not productive
- Instead, opt for piecewise construction 
- Builder provides an API for constructing and object step-by-step

**When piecewise object construction is complicated, provide an API for doing it succinctly.**