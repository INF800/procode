### 01. Array

Java

```java
import java.util.ArrayList;
import java.util.Arrays;

// 1. default initialisation
ArrayList<Integer> arr = new ArrayList<Integer>();

// 2. initialisation with elements
ArrayList<Integer> arr2 = new ArrayList<Integer>(Arrays.asList(1,2,3));

// System.out.println(arr); // []
// System.out.println(arr2); // [1,2,3]

```

### 02. Array of arrays

Java

```java
import java.util.ArrayList;

ArrayList<ArrayList<Integer>> arr = new ArrayList<ArrayList<Integer>>();
// ArrayList<Integer> ele = new ArrayList<Integer>();
// ele.add(0);
// arr.add(ele);
// System.out.println(arr); [[0]]
// System.out.println(ele); [0]
```
