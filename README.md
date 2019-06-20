# golang
I'm new to go, I've heard a lot about it, I'll document the process and keep putting small programs written in go as I progress. I'm planning to contribute to Kubernetes, since, Kubernetes is written in go, I've to learn go. I'll also put up a tutorial in The Programming Foundation once I get a job. I'll reference a lot of C++ and Python code and processes in this unofficial documentation/learning process in order to demonstrate familiarity.

<b> Features: </b> Statically typed, compiled language

<b> My understanding of Go - A little background on my academic journey</b>
<br>
I started my freshman year at SDState in 2015, I was taught C++ and C in the first semester along with Python Informatics. Later, when I transferred to Foothill, I stayed with C++ up until last month. I also took Java 1A at Foothill but I had to drop that class since I performed terribly and didn't understand a thing. Coming from a C++ background and submitting assignments written in that language were fine. But now that I've started preparing for technical interviews since last month, Python is my preferred language for solving coding challanges. Although, I wasn't very regular with Python syntaxes, Google's secret foobar challanges made me more comfortable with them. Go seems like an interesting language. It has the best of both C++ and Python. Currently, I'm in the "hello world" stage. Although, putting the data type after declaring the variable seems kinda weird, I'm planning to learn it slowly.

<b>Setup Process</b> <br>
Setting up golang is slightly different than C++ and Python. For C++, all you need is a compiler like clang or gcc. For Python you just need to install Python in your machine. Since, golang is a compiled language, the process of compiling go programs is the same as C++. For go, a workspace directory needs to be created but before, golang should be installed first,<br>

<code>brew install golang</code> <br>

To setup the workspace directory, you need to have the name of the workspace which in this case is the go directory, inside it should be a directory named src in which the .go program will reside. The structure looks like this, <br>

![tree](https://github.com/bootkernel/golang/blob/master/Screen%20Shot%202019-06-19%20at%208.17.37%20PM.png)

For a well documented setup process, please refer to the official getting started documentation: https://golang.org/doc/install

<b>Compile</b> <br>
To compile a hello.go file, run the below command from the directory in which hello.go is located,

<code>go build hello.go</code> <br>

Keep in mind, the green highlighted hello in the hello directory is the binary that was compiled using this above command. Just like C or C++ this can be run using,<br>

<code>./hello</code> <br>

<b>Simple Hello World program in go:</b>
<br>

```go
package main

import "fmt"

func main() {

  fmt.Println("Hello")

}

```
<b>Analysis of the above program,</b>
<br>
In Python, I could write this in a single line,<br>
```python
print("Hello")
```
In C++ this would be,
<br>

```cpp
#include <iostream>

using namespace std;

int main() {

  cout << "Hello" << endl;

return 0;
}
```
