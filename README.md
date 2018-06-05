# Ggg.Architecture
Software Architecture related books, links, quotes etc.

- If you think good architecture is expensive, try bad architecture.
- Heaps are binary trees for which every parent node has a value less than or equal to any of its children.
- all programs can be constructed from just three structures: sequence, selection, and iteration.
- Science does not work by proving statements true, but rather by proving statements false.
- mathematics is the discipline of proving provable statements true. Science, in contrast, is the discipline of proving provable
statements false.
- a heap is a good structure for implementing schedulers
- If the modules in your system can be deployed independently, then they can be developed independently by different teams. That’s independent developability.
- All race conditions, deadlock conditions, and concurrent update problems are due to mutable variables. You cannot have a race condition or a concurrent update problem if no variable is ever updated. You cannot have deadlocks without mutable locks.
- Architects would be wise to push as much processing as possible into the immutable components, and to drive as much code as possible out of those components that must allow mutation.
- Event sourcing is a strategy wherein we store the transactions, but not the state. When state is required, we simply apply
all the transactions from the beginning of time.
- If we have enough storage and enough processor power, we can make our applications entirely immutable—and, therefore, entirely functional.
- An enumeration is a set of symbolic names (members) bound to unique, constant values.
- At the start of any design effort, the person who most wants to be team leader is least likely to be capable of it.
- Sometimes, the fastest way to get to the end is to throw everything out and start over.
- There is never a single right solution. There are always multiple wrong ones, though.
- A bad design with a good presentation is doomed eventually. A good design with a bad presentation is doomed immediately.
- Do what you can, where you are, with what you have.
- A designer knows that he has achieved perfection not when there is nothing left to add, but when there is nothing left to take away.
- Dynamically typed languages create systems that are more flexible and less tightly coupled than statically typed languages. 
- Don’t override concrete functions. Concrete functions often require source code dependencies. When you override those functions, you do not eliminate those dependencies—indeed, you inherit them. To manage those dependencies, you should make the function abstract and create multiple implementations.
- Components are the units of deployment. They are the smallest entities that can be deployed as part of a system. In Java, they are jar files. In Ruby, they are gem files. In .Net, they are DLLs. In compiled languages, they are aggregations of binary files. In interpreted languages, they are aggregations of source files. In all languages, they are the granule of deployment.
- If something is exceptional you should throw an exception. 
- A good architect maximizes the number of decisions not made.  
