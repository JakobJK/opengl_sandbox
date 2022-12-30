# openGL playground

## Polies & Ponies - Let's go!

```
$jaker@jake: g++ main.cpp glad.c -o output.out -L lib -lglad -lglfw
```


# Q ? 


- stride?
    - space between consecutive vert attributes. Can be left at 0 if vert attributes are tightly packed.
- Vertex Array Obj?
    - any subsequent vertex attribute calls from that pooint on will be stored inside the VAO. Makes it performent as you only have to make the config calls once when we want to draw the object. It will make it easy to switch vertex data and attribute configs.
