# My first program in c++

* Alternative 1

```c++
#include <iostream>

int main()
{
        std::cout << "Hello World!" << std::endl;

        return 0;
}
```
----

## Second program

* data types in c++ `int, double, char, string, double` and input/output

```c++
#include <iostream>

using namespace std;

int main()
{
        int nombre = 4;
        int playa = 8;
        int teclado = 2;
        double noExact = 9.8;
        char course = 'a'; // using single quotes
        string hello = "helo"; // using double quotes
        bool isTable = true; // true = 1 or false = 0

        string inputName = "";

        cout << playa << ' ' << teclado << ' ' << noExact << ' ' << course << ' ' << hello << ' ' << isTable << endl;

        cin >> inputName;
        cout << inputName << endl;

        return (0);
}
```

---

## third program

* Capture a sequence of strings

```c++
#include <iostream>
#include <string>

using namespace std;

int main()
{
        string hello = "";
        getline(cin, hello);

        cout << hello << endl;

        return (0);
}
```

---




## Structure of directories

```bash
$ tree
.
├── README.md
└── main.cpp

0 directories, 3 files
$
```

## Run

* Compiler program

```bash
$ g++ -o ./helloworkd ./main.cpp
```

* Program compiled

```bash
$ ls -la helloworkd
-rwxr-xr-x  1 juurbano  1010544492  39639 Nov 13 11:59 helloworkd
$
```

```bash
$ g++ -o ./helloworkd ./main.cpp
$ ./helloworkd
Hello World!
$
```
