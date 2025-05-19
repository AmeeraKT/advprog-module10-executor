# Advanced Programming Module 10

## Asynchronous Programming - Timer and Executor

### Reflection

##### Experiment 1.2:
![image1](images/image1.jpg)

In the image above, heyhey is printd first before howdy! and done! because it is located outside of the asynchronous function while the latter two are inside one. The asynchronous function is called by a spawner which is a process that does not stop the main process while running in the background. The main function immediately goes to the next instruction given which is after the asynchronous function which is the new print function for 'hey hey', which is printed first before 'howdy!' and 'done!'.