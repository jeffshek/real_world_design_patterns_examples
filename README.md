# **Design Patterns In Real World Applications**

*Some assumptions are made that a reader is familiar with the underlying design pattern discussed.* 

This is not about how to implement a specific pattern, but an illustration where certain designs come in handy. My expertise lies in Python, so while this list should be language-agnostic, some Pythonic things may slip.



## **Creational Patterns**
1. Abstract Factory
	* 
1. Builder
	* 
1. Factory Method
	* 
1. Monostate
	* Same as Singleton examples, just implementation is slightly different.
1. Singleton
	* External API that throttles max connections. | Force usage of single API instantiation.
1. Prototype
	* 

## **Behavioral Patterns**
1. Chain of Responsibility
	* Exceptions can be operated by numerous interfaces.
1. Command
	* Job Queues | Passing jobs that can be executed by any machine.
1. Interpreter
	* 
1. Iterator
	* 
1. Mediator
	* Mailing Lists & Chatrooms | Mediator decides how and what messages recipients should recieve. 
1. Memento
	* Undo Functionality | Snapshot of before and after action.
1. Null Object
	* 
1. Observer
	* 
1. Null State
	* 
1. Strategy
	* 
1. State
	* 
1. Template Method
	* 
1. Visitor
	* Calculating taxes in different regions on sets of invoices would require many different variations of calculation logic. Implementing a visitor allows the logic to be decoupled from the invoices and line items.


## **Structural Patterns**

1. Adapter
	* 
1. Bridge
	* 
1. Composite
	* 
1. Decorator
	* 
1. Facade
	* Python's os.path | Simplify extensive upstream interface. Simplies split + indexing
1. Flyweight
	* 
1. Proxy
	* 


## **Credit**

* [Alex Martelli - Design Patterns in Python](http://www.aleax.it/gdd_pydp.pdf)
* [DZone - Design Patterns](https://dzone.com/refcardz/design-patterns)
* [Gang of Four - Design Patterns](https://en.wikipedia.org/wiki/Design_Patterns)
* [Toptal - Python Design Patterns](https://www.toptal.com/python/python-design-patterns)
* [Source Making - Design Patterns Explained Simply](https://sourcemaking.com/design-patterns-ebook)