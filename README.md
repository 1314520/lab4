# lab4
A

00000000004004b4 T _Z7averagePdRd是double average(double *n1,double & n2)的 encoded identifier
00000000004004e2 T _Z7averageif是int average(int n1, float n2)的encoded identifier
000000000040050a T main是int main()的encoded identifier



B
output是：
18
48
48
88
原因：
電腦讓不同變數有不同的記憶體存取大小，但因為指標原本就設定好為8byte，所以不管何種型態皆為一樣。
