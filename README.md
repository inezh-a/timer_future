### **Understanding how it works.**
![understanding.png](images/understanding.png) <br>
> Screenshot shows that the added sentence after spawner.spawn(); got printed first before the two print commands in spawner.spawn();. As I understand it, asynchronous code in Rust allows for operations to run concurrently without blocking the execution of the entire program. The results indicates that the program managed to execute the the outside print command first before the spawner did it's job, due to it not needing to wait for the spawner to finish.
