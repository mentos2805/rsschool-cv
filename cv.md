## Contact Info
**First name:** Vlad

**Last name:** Scovorodkin

**Mobile phone:** +37525 795-26-26 (Life)

## Summary

I'm passionate about technology.

I hope that your courses will help me not only use technology but develop it.

## Skills
* Basic knowledge of **HTML** and **CSS**
* **JS**, **Python**: solved simple algorithmic tasks
* **Ubuntu** is my primary laptop OS
* **Linux terminal**, **git** basics
* Offfice software: **Excel**, **Word**, **PowerPoint**
* **Teamwork skills**:  communication and conflict resolution
* **Sales skills**

## Code Examples 
My last task in the **python programming**:
```Python
   n, m = [int(i) for i in input().split()]
   a = [[int(i) for i in input().split()] for j in range(n)]
   Rmax, Cmax = 0, 0
   Elmax = a[Rmax][Cmax]
   for i in range(n):
        for j in range(m):
            if Elmax < a[i][j]:
                Elmax = a[i][j]
                Rmax, Cmax = i, j
    print(Rmax, Cmax)
 ```
**Javascript** code example:
```Javascript
function check(str, bracketsConfig) {
   var closedCorresp = {};
   var similar = {}
   for (var i=0;i<bracketsConfig.length;i++) {
      var openBracket = bracketsConfig[i][0];
      var closedBracket = bracketsConfig[i][1];
      if (openBracket == closedBracket) {
         similar[openBracket] = true;
      } else {
         closedCorresp[closedBracket] = openBracket;
      }
   }
   var st = [];
   for (var i=0; i<str.length;i++) {
       var symbol = str[i];
       var stackHead = st[st.length-1];
    if (similar[symbol]) {
       if (stackHead == symbol) {
           st.pop();
       } else {
           st.push(symbol);
       }
     } else if (!closedCorresp[symbol]) {
        st.push(symbol);
    } else {
        if (st.pop() != closedCorresp[symbol]) {
            return false;
        }
     }
  }
  return (st.length == 0);
 }
```

## Education and Experinсe

I solved tasks on an online platform such as:
* [codewars.com](https://codewars.com)
* [codecademy.com](https://codecademy.com)
* [pythontutor.ru](http://pythontutor.ru)
* [learn.javascript.ru](https://learn.javascript.ru)

## English level

A2 (Elementary English).

I always improve my English at [www.duolingo.com](https://www.duolingo.com) and watching simple films.
