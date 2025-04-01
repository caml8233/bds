combines multiple variables into a single split variable to extend the character length limit, using FIFO for limit handling—deleting the earliest object(s) when the limit is exceeded.

currently only tested on json like 
```
{
  "this":{
    "structure":"xxx"
  },
  "yy":{
    "zzz":"aaa",
    "bb":9999999
  },
  ...
}
``` 
you might need to edit some of the logic for different structure.

#### example using 50 max_length
![image](https://github.com/user-attachments/assets/73c07934-786a-4a4b-989c-0322409361c1)

regular textsplit version soon.
