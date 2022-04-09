- 👋 Hi, I’m @9157393933
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
9157393933/9157393933 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
#include<math.h>
void main(){
    
    //Explicit

    float p,r,t;
    printf("Enter the Values of p, r and t : ");
    scanf("%f %f %f",p,r,t);
    int i=(int)p*r*t/100;
    int a=(int)(p+i);

    printf("The Simple Interest is %d and Payable Amount is %d",i,a);
}
