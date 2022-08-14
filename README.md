# Plato: Technical Assignment - data persistence layer in Go+Postgres with CRUD
---


## Assignment Details
Create a persistent layer that works with _PostresSql_ and has an ability to batch process incoming requests
based on the scheduler work cycle.


The __PUT__ method processes db timestamp updates for each resource id it receives.


The __GET__ method returns an updated timestamp based on the resource id.

```
__NOTE__: this is a quick write-up to demonstrate the ability to work with _go_ sql module,
running parameterized and prepared statements, the ability to run multiple _goroutines_,
work with _channels_ and _mutex_ synchronization primitives. As such, this is not a complete
or, for that matter, a working soluiton.
```

There was a limit to complete the write-up in under an hour and present the code for examination
by a potential employer. The code contains some rough and quick thinking to put together a rather logically coherent
flow of operations. 


My __moviecoin__ project contains a more complete, yet, work-in-progress at the moment, project, that aims to have 
a complete and working __pow__ blockchain coin solution. Feel free to either clone or contribute to my __moviecoint__
project.



