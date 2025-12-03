# NON-REGISTER-CPU

Non-Register Cpu is the cpu that is the eliminate the traditional register of the cpu.
Then, how to load the codes? Because of the caches and the DMA. 

DMA do the load and blow the codes into the cache, and the Controlling unit (a.k.a CU) load the code.
This cpu is Queue-Based(First in, First out) structure. This concepts are releated the RPU, the Rust processing Unit.
Also, its scalable, stackable to attach the side to side too. That is much available for the parallel operations.
