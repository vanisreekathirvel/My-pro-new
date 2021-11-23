# SOURCE FILE 
## main.c 

#include<stdio.h> 

#include"person.h"

int main(char b[])

{

printf("person name: %s\n",name(b)); 

printf("if you get offer letter whether 'yes' or 'no'");

printf("you are %s\n",letter(b));

printf("if you get ps number, email whether 'yes' or 'no'");

printf("ps number,email %s\n",num(b));

if(num(b)=='partially')

{

printf("required IT Connect\n"); 

} 

else if(num(b)=='not available') 

{ 

printf("if you submit service agreement whether 'yes' or 'no'");

printf("you %s\n",avai(b));

}

printf(" you have GEA learing\n");

printf("if you log in ssc portal whether 'yes' or 'no'"); 

printf("ssc portal %s\n", log(b));

if (log(b)=='log in')

{

printf("if your profile updated whether 'yes' or 'no'");

printf(" your profile %s\n", up(b));

}

printf("if you log in rainbow portal whether 'yes' or 'no'");

printf("rainbow %s\n", log1(b));

if (log1(b)=='log in') 

{ 

printf("if your profile updated whether 'yes' or 'no'");

printf(" your profile %s\n", up1(b));

}

printf(" if you log in submitty portal whether 'yes' or 'no'");

printf("submitty %s\n", log2(b));

if (log2(b)=='log in') 

{

printf("if your profile submission updated whether 'yes' or 'no'");

printf(" your profile submission %s\n", up2(b)); 

} 

return 0;

}

}
