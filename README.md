# Rust Ethereum utility library 

Perpose is to group parts of code that are needed for rust ethereum client.

Currently it contains:
* Queue:
  * AsyncQueue: VecDeque that can be used to send Item from one thread to another. Max items and bathes execution are supported.
  * ExecutionQueue: It spins one thread and uses closure to executes Item in queue. It uses AsyncQueue as queue.