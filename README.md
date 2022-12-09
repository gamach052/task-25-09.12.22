###  [Task 7 kyu](https://www.codewars.com/kata/6391fe3f322221003db3bad6/train/java)

ou are given an input (n) which represents the amount of lines you are given, your job is to figure out what is the maximum amount of perpendicular bisectors you can make using these lines.


### My solution
```Java
public class Perpendicular {
    public static int maxBisectors(int n) {
        if (n%2==0){
            return (n/2)*(n/2);
        }
        else {
            return (((n-1)/2)*((n-1)/2)+n/2);
        }
    }
}

```

### Fav solution
```Java
public class Perpendicular {
    public static int maxBisectors(int n) {
        return (int) Math.pow((double) n/2, 2);
    }
}
```
I like this solution because I like it
