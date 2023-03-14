# Glory of the Garden

We get a beautiful image of a garden: 

![garden](garden.jpg)

But this doesnt show us a lot. 

This can be solved in a couple of different ways, the first things that come to mind is `cat` and `strings`

```bash
cat garden.jpg | grep picoCTF

-- or

strings garden.jpg | grep picoCTF
```

In this instance `cat` with `grep` will not work, as the flag is in a string, but you can still just `cat` the file and your terminal will show the flag at the bottom of the output. 

Using `strings garden.jpg | grep picoCTF` we get:  
Here is a flag "picoCTF{more_than_m33ts_the_3y33dd2eEF5}"