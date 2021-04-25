# code.md



[back to README.md](README.md)



## 代码清单

### 1 java代码

```java

import java.util.Scanner;
public class ScannerTest {
    public static void main(String[] args){
        Scanner scanner=new Scanner(System.in);
        System.out.print("请输入一个数");
        int a=scanner.nextInt();
        System.out.printf("%d的平方是%d\n",a,a*a);
    }
}
```

### 2 C++代码

```c++
#include <iostream>
using namespace std;
int main()
{
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

### 3 python代码

```python
def bubble_sort(nums):

    for i in range(len(nums) - 1):

        for j in range(len(nums) - i - 1):

            if nums[j] > nums[j + 1]:

                nums[j], nums[j + 1] = nums[j + 1], nums[j]

    return nums
```

### 4 shell 脚本

```shell
#!/bin/bash 
if [ -f "$FAIL_FILE" ]
  then 
    rm -rf "$FAIL_FILE" 
    echo `date`" FILE IS EXISTS: "$FAIL_FILE 
fi
```

