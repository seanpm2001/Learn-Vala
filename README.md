
***

![/Vala_Logo.svg](/Vala_Logo.svg)

### Learning Vala

I started learning the Vala programming language when I moved to GitHub, late into 2020. As of 2021 November 23rd, I don't know too much about the language. This document will go over my knowledge of the Vala programming language so far.

#### Comments in Vala

Comments in Vala are similar to languages like C, C++, Java, CSS, etc.

```vala
// This is a single line comment
/* This is also a single line comment */
/* This is
a multi-
line com-
ment */
```

#### Hello World in Vala

This is a simple Hello World program in Vala:

```vala
void main() {
	print ("Hello World\n");
}
```

#### Integers in Vala

Integers in Vala are standard and similar to most programming languages:

```vala
int x = 1;
```

#### Floating values in Vala

Vala supports the `float` keyword. It stores a decimal value. I have not tested its bitwise limitation yet (if it can handle 2^64)

```vala
float pi = 3.14;
```

#### Strings in Vala

Vala supports the `string` keyword.

```vala
string str = ("Stringy string");
```

#### Double keyword in Vala

Vala supports the `double` keyword (double precision floating point), similarly to how the C programming language handles it.

```vala
double trouble = 2
```

I don't know how to work this yet.

_/!\ This example has not been tested yet, and may not work_

#### Classes in Vala

Vala supports classes.

```vala
class valaClass() {
	void main() {
		print("Vala Class returns true");	
	}
}
```

_/!\ This example has not been tested yet, and may not work_

#### Return statements in Vala

Vala supports the `return` statement.

```vala
int value1 = 2;
return value1();
```

_/!\ This example has not been tested yet, and may not work_

#### Break keyword in Vala

```vala
break;
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Other knowledge of Vala

1. Vala is a semicolon and curly bracket language

2. Vala uses 2 file extensions: `*.vala` or `*.vapi`

3. Vala is developed by the GNOME Foundation

4. I am not sure whether Vala works well outside of Linux/GNOME

5. No other knowledge of the Vala programming language

***
