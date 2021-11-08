# An-Implementation-of-Multiplication-in-Finite-Field-Extensions-with-a-Special-Prime-Number-
The final project

The security test use the open source “dudect”, and it should be test individually(rather than test with “correctness” and “efficiency” at the same time). The document is “testsecurity.zip”.
Once we have decompressed it, there are 3 step to test it: 
1.Type “make clean”
2.Type “make main”
3.Type “./main-o2” to execute it.
The default testing is testing the security of quadratic extension, if we want to test others, we should focus on the function “int main2()” in “main.c”. All the candidate testing function are in this function.
