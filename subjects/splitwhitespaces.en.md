## splitwhitespaces

### Instructions

Write a function that separates the words of a `string` and puts them in a `string` array.

The separators are spaces, tabs and newlines.

### Expected function

```go
func SplitWhiteSpaces(str string) []string {

}
```

### Usage

Here is a possible program to test your function :

```go
package main

import (
	"fmt"
	piscine ".."
)

func main() {
	str := "Hello how are you?"
	fmt.Println(piscine.SplitWhiteSpaces(str))
}
```

And its output :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
[Hello how are you?]
student@ubuntu:~/[[ROOT]]/test$
```
