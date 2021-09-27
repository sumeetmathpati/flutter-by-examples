---
title:  "Variables"
categories: main
description: "Learn about variables in Dart"
serial: 1
---

# Simple Variables

Declaring variables in Dart is similar to may other languages (like C, C++, or Java). **First we specify the type of the variable, then variable name, and then optionally we can also initialize the variable at the time of declaration.**

Below is the Dart code in which variabels of some primitive types are used.

{% highlight c %}
void main() {
  int myInt = 10;
  double myDouble = 1.2;
  num myNumber = 100;
  bool myBool = true;
  bool myAnotherBool = false;
  int myNullValue;

  print(myInt);
  print(myDouble);
  print(myNumber);
  print(myBool);
  print(myAnotherBool);
  print(myNullValue == null);
}

/*
Output:
10
1.2
100
true
false
true
*/
{% endhighlight %}
[Open above code in Dartpad](https://dartpad.dev/?id=4975ec847f4ec573e7c903d2e8f2462a)