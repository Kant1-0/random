# C++ class - Unique Random Numbers
It can compute an unique int or float between a given range. Don't forget to init once srand at the beginning of your program.<br>
*Warning: Initing srand several times along the program can mess up the process of computing an unique random number.*

```c++
int   main(int argc, char* args[])
{
    srand( time( NULL ) );
    
    /* Your long code using random numbers */
    
    return 0;
}
```

There's not so much fanciness here.
