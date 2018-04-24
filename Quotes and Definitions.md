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