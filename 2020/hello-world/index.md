# Hello World


一切都要从 《The C Programming Language》 中的 "Hello World" 说起

```c
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```

## Go 泛型

### 示例

[Go: The Next Step for Generics](https://blog.golang.org/generics-next-step)

```go
// https://go2goplay.golang.org/p/DLyfY7AX_AZ
func Print(type T)(s []T) {
	for _, v := range s {
		fmt.Print(v)
	}
}

func main() {
	Print([]string{"Hello, ", "playground\n"})
	Print([]int{1, 3})
}
```
