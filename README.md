This program can be used to create a unique ring "buffer" stack of stack size "length"

When you add element in stack, it checks if alreaedy present. In that case discard and return false else add and return true

Note the stack never grows beyond "length" elements. If it grows, the earlier elements are trimmed to maintain the length of stack as defined during initialisation


Note that you can define string or int or any other variable type just when you add to the stack. This is because the program uses interface{} and the moment you add the first element, it automatically gets to know whether you are chosing string, int, byte or whatever type


Yes, interface is a powerful feature of Go Lang and I love it :-) 
