# What is a firmware library?
  A firmware library is a collection of reusable functions that provide a clean interface to hardware.

# Why APIs are important in embedded systems?
In industry:
- firmware is reused across projects
- hardware may change, APIs should not
- clear APIs reduce bugs and development time
  
# What was understood from the lab code?
- gpio.h: the definition of constant and the declaration of the exposed API  
- gpio.c: the implementation of the API 
- main.c: the entrance point of the program and where the API is used by the application  
