### 103

#### basic usage
![](./pics/usage1.png)

![](./pics/usage2.png)

![](./pics/usage3.png)


````
it seems that when i enter 3 i got to place where the program
is interacting with me at first Segmentation fault which is good
signal probably no canary if it was i would got stack smashing
detected probabaly
````

#### basic recon

![](./pics/basic_recon.png)

#### *what the binary is using*

![](./pics/imports.png)

````
we see that __isoc99_scanf means that i will try to override something
and we see also system so probably a shell will be given to us
and i think that we will have to interact with strncmp somehow
````
