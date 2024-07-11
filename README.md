/*FIRST ASSIGNMENT*/

/*Write a C++ program to print "Hello, world!" to the screen.
#include<iostream>
using namespace std;

int main()
{
    cout<<"Hello, world!"<<endl;
    return 0;

}
*/


/*Write a C++ program that declares an integer variable called "x" and assigns it the 
value 10. Then, print the value of "x" to the screen.

#include<iostream>
using namespace std;

int main()
{
    int x = 10;
    cout<<x<<endl;
    return 0;

}
*/

/*3)Write a C++ program that declares a floating-point variable called "y" and assigns 
it the value 3.14. Then, print the value of "y" to the screen.

#include<iostream>
using namespace std;

int main()
{
    float y = 3.14;
    cout<<y<<endl;
    return 0;
}
*/

/*4)Write a C++ program that declares a character variable called "c" and assigns 
it the value 'a'. Then, print the value of "c" to the screen.
#include<iostream>
using namespace std;

int main()
{
    char c='a';
    cout<<c<<endl;

    return 0;
}
*/

/*5)Write a C++ program that declares a boolean variable called "b" and assigns
it the value true. Then, print the value of "b" to the screen
#include<iostream>
using namespace std;

int main()
{
    bool b = true;
    cout<<b<<endl;

    return 0;
}
*/

/*6)Write a C++ program that declares two integer variables called "a" and "b" and assigns them the values 5 and 
10, respectively. Then, calculate and print the sum of "a" and "b" to the screen.

#include<iostream>
using namespace std;

int main()
{
    int a=5, b=10;
    cout<<a+b<<endl;
    return 0;
}
*/

/*7)Write a C++ program that declares two floating-point variables called "p" and "q" and assigns them the values 
2.0 and 3.0,respectively. Then, calculate and print the product of "p" and "q" to the screen.

#include<iostream>

using namespace std;
int main()
{
    float p = 2.0, q = 3.0, r;
    r = p+q;
    cout<<r<<endl;

    return 0;

}
*/

/*8)Write a C++ program that declares two integer variables called "m" and "n" and assigns them the values 7 and 3, 
respectively. Then, calculate and print the result of "m" divided by "n" to the screen.

#include<iostream>
using namespace std;

int main()
{
    int m = 7, n = 3;
    cout<<m/n<<endl;

    return 0;

}
*/

/*Write a C++ program that declares a character variable called "ch" and assigns 
it the value 'A'. Then, print the ASCII value of "ch" to the screen.

#include<iostream>
using namespace std;

int main()
{
    char ch = 'A';
    cout<<int(ch)<<endl;

    return 0;

}
*/
/*10)Write a C++ program that declares two boolean variables called "x" and "y" and assigns them the values true and false, 
respectively. Then, print the result of "x AND y" on the screen.

#include<iostream>
using namespace std;

int main()
{
    bool x = true, y = false;
    cout<<x<<  y  <<endl;
    
    return 0;

}
*/
/*11)Write a C++ program to print the following message on the console: Hello, my name is "John Doe" and I'm learning C++. Your program should use 
escape sequences to include quotation marks around the name "John Doe".

#include<iostream>
using namespace std;

int main()
{
    cout<< "Hello, my name is \"John Doe\" and I'm learning C++" <<endl;

    return 0;
}
*/

/*SECOND ASSIGNMENT*/
/*1)#include<iostream>
using namespace std;

int main()
{
    int x;
    cout<<"Enter the number: ";
    cin>>x;

    if (x>=90)
    {
        cout<<"A"<<endl;
    }
    else if (x>80 && x<89)
    {
        cout<<"B"<<endl;
    }
    else if (x>70 && x<79)
    {
        cout<<"C"<<endl;
    }
    else if (x>60 && x<69)
    {
        cout<<"D"<<endl;
    }
    else{
        cout<<"F"<<endl;
    }
    
    return 0;   
}
*/


/*2)#include<iostream>
using namespace std;

int main()
{
    int y;
    cout<<"Enter the year: ";
    cin>>y;

    if (y % 4 == 0 && y % 400 == 0)
    {
        cout<<"its a leap year";
    }
    else if (y % 100 !=0)
    {
        cout<<"not a leap year";
    }
    
    else {
        cout<<"not a leap year";
    }
    return 0;
}
*/

/*#include<iostream>
using namespace std;

int main()
{
    int a;
    cout<<"Enter the number: ";
    cin>>a;

    if (a>0)
    {
        cout<<"The number is positive";
    }

    else if (a<0)
    {
        cout<<"The number is negative";
    }

    else if (a==0)
    {
        cout<<"The number is ZERO";
    }
    
    else{
        cout<<"Nmber in valid"<<endl;
    }
    return 0;
}
*/

/*FIFTH ASSIGNMENT*/

/*1)Write a C++ program to calculate the area and perimeter 
of a rectangle, given its length and width as input.

#include<iostream>
using namespace std;

int main()
{
    int l=10, b=10, s;
    s=l*b;
	cout<<"area of rectangle:"<<s<<endl;

    
    return 0;
}
*/

/*2)Write a C++ program to convert Celsius to Fahrenheit, 
given the temperature in Celsius as input.

#include<iostream>
using namespace std;

int main()
{
    float Celsius, Fahrenheit;

    cout<<"Enter the value of celsius: ";
    cin>>Celsius;

    Fahrenheit = (Celsius * 9/5) + 32;

    cout<<"Fahrenheit = "<<Fahrenheit<<endl;
    return 0;

}
*/
/*3)Write a C++ program to calculate the average of 
three numbers, given the three numbers as input.

#include<iostream>
using namespace std;

int main()
{
    int a=2,b=3,c=4,d;

    cout<<"average: "<<((a+b+c)/3)<<endl;

    return 0;
    
}
*/

/*4)Write a program that finds the largest among three numbers.

#include<iostream>
using namespace std;

int main()
{
    int a,b,c;

    cout<<"Enter the number a: ";
    cin>>a;
    cout<<"Enter the number b: ";
    cin>>b;
    cout<<"Enter the number c: ";
    cin>>c;

    if (a > b && a > c)
    {
        cout<<"A is the largest";
    }
    else if (b > a && b > c)
    {
        cout<<"B is the largest";
    }
    
    else if (c > a && c > b)
    {
        cout<<"C is the largest";
    }
    
    else
    {
        cout<<"Number doesnt exit";
    }

    return 0;    
}
*/

/*5)Write a program that checks if a given character is a vowel or a consonant.
#include<iostream>
using namespace std;

int main()
{
    char vowel[6]={'a','e','i','o','u'};

    char a1;
    int i;
    cout<<"Enter the letter: ";
    cin>>a1;
    
    for(i=0; i < 5; i++)
    {
        if (vowel[i]==a1)
       {
        cout<<"The entered letter is VOWEL"<<endl;
        }
       else
       {
        cout<<"The enteres letter is CONSONANT"<<endl;
        }
       }
    return 0;
}
*/

/*7)Write a program to find the sum of all even numbers 
between 1 to n, where n is an input from the user

#include<iostream>
using namespace std;

int main()
{
    int n;
    cout<<"Enter the number: ";
    cin>>n;

    
}
*/


/*
#include<iostream>
using namespace std;

int main()
{
    int i,size;
    string word;
    cout<<"Enter the word: ";
    cin>>word;

    size = word.length();
    cout<<"length: "<<size<<endl;

    for (i=0;i<size/2; i++)
    {
        swap(word[i],word[size-i-1]);
    }
    cout<<"\nafter reversing the stirng: "<<word<<endl;
    
    return 0;

}
*/


/*
1)
#include<iostream>
using namespace std;

int main()
{
    int a,i,sum=0;
    cout<<"enter the elements: ";
    cin>>a;

    for(i=0;i<=a;i++)
    {
        sum = sum+i;
    }

    cout<<"SUM: "<<sum<<endl;
    
    return 0;
}*/


/*
3)
#include<iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int array[5]={4,3,5,1,2};
    int n= sizeof(array) / sizeof(array[0]);

    std::sort(array,array+n);

    for(int i=0;i<n;++i)
    {
        cout<<"sorted array: "<<array[i]<<endl;
    }

    return 0;
}*/

/*
#include<iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{
    char str0[] ="TODAY'S NEWS";
    char str1[] = "tarun is feeling horny";
    char str2[] = "raaghav and srinath is gay";

    cout<<strlen(str1)<<endl;
    cout<<strlen(str2)<<endl;

    cout<<(str0)<<endl;
    cout<<(str2+12)<<endl;
    cout<<(str1+9)<<endl;
    cout<<strcmp(str1,str2)<<endl;
    
    cout<<strcat(str1,"!!")<<endl;
    cout<<strcat(str2,"!!")<<endl;
    return 0;

}


// C++ program to find maximum 
// element 
#include <bits/stdc++.h>
using namespace std;

// function to find the maximum element 
int findMaximum(int arr[], int low, int high) 
{ 
	int max = arr[low]; 
	int i; 
	for (i = low + 1; i <= high; i++) 
	{ 
		if (arr[i] > max) 
			max = arr[i]; 
		
		// break when once an element is smaller than 
		// the max then it will go on decreasing 
		// and no need to check after that 
		else
			break; 
	} 
	return max; 
} 

/* Driver code
int main() 
{ 
	int arr[] = {1,2,3,4,5}; 
	int n = sizeof(arr)/sizeof(arr[0]); 
	cout << "The max number is: " << findMaximum(arr, 0, n-1); 
	return 0; 
} 

// This is code is contributed by rathbhupendra

#include <stdio.h>
#include <string.h>
int main(){
    char first[]="This is orange juice";
    char second[]="orange";
    int i,j;
    int found = 0;
    //length of orange is 6 and first sentence is 20
    //we will iterate and check if the characters form the word orange or not
    for(j=0;j<=15;j++){
      //checking if orange or not
      //6 is the length of orange
      int k=0;
      for(i=j;i<j+6;i++){
        if(first[i]!= second[k]){
          break;
        }
        else{
          k++;
        }
      }
      //if k>5 means orange is found
      //because if found then k will increase uptill 6
      if(k>5){
        found = 1;
        break;
      }
    }
    if(found == 1){
      printf("Found\n");
    }
    else{
      printf("Not found\n");
    }
    return 0;
}



#include<iostream>
using namespace std;
int main()
{
    int arr[5]={50,40,10,20,30};
    int count=0;
    int i;
    for(int i=0;i<=4;i++)
    {
    if(arr[i]!=20)
    {
        count = count+1;
    }
    else{
        printf("%d",count);
    }
    }
    return 0;
}

#include<iostream>
using namespace std;
int main()
{
    int i,count=0;
    string str;
    int n = str.length();
    cout<<"enter value: "<<endl;
    cin>>str;
    
    for(i=0;i<n;i++)
    {
        if (str[i]==1)
        {
            count = count +1;
        }
        else if(count==1)
        {
            cout<<"YES";
        }
        else{
            cout<<"NO";
        }
        
        
    }
   
    return 0;
}
*/
/*

#include <iostream>
using namespace std;

int main()
{
    int n,i,j;
    cout<<"Enter the number: "<<endl;
    cin>>n;

    for(i=0;i<n;i++)
    {
        for(j=0;j<n;j++){
        cout<<" * ";
    }
    cout<<"\n";
    }
    return 0;
}

* * * * *
* * * * *
* * * * *
* * * * *
*/

/*
#include<iostream>
using namespace std;
int main(){
    
    int n,i,j,count=0;

    cout<<"Enter n: ";
    cin>>n;

    for(i=0;i<n;i++)
    {
        for(j=0;j<i+1;j++){
        count = count+1;
        cout<<count;
        }
    
    cout<<"\n";
    }

    return 0;
}
*/
/*
#include<iostream>
using namespace std;
int main(){
    
    int n,i,j;

    cout<<"Enter n: ";
    cin>>n;

    for(i=0;i<n;i++)
    {
        for(j=i;j<n;j++){
        cout<<" * ";
        }
    
    cout<<"\n";
    }

    return 0;
}
 *  *  *  *  * 
 *  *  *  *
 *  *  *
 *  *
 *
*/
/*
#include<iostream>
using namespace std;
int main(){
    
    int n,i,j,k;

    cout<<"Enter n: ";
    cin>>n;

    for(i=0;i<n;i++)
    {
        for(j=n;j>i;j--){
            cout<<" ";

        }
        for(k=0;k<i;k++){
        cout<<"* ";
        }
    
    cout<<"\n";
    }

    return 0;
}
  *
 * * 
* * *
*/
/*
#include<iostream>
using namespace std;
int main(){
    
    int n,i,j,k;

    cout<<"Enter n: ";
    cin>>n;
    for(i=0;i<n;i++)

    {
        for(j=n;j>0;j--){
            if(i>=j)
            {
                cout<<" *";
            }
            else{
                cout<<" ";
            }
        }
            cout<<"\n";
    }
    return 0;
}

  *
 * * 
* * *
*/

/*
#include<iostream>
using namespace std;
int main(){
    
    int n,i,j,k;

    cout<<"Enter n: ";
    cin>>n;
    for(i=0;i<n;i++)

    {
        for(j=n;j>0;j--){
            if(i>=j)
            {
                cout<<"*";
            }
            else{
                cout<<" ";
            }
        }
            cout<<"\n";
    }
    return 0;
}

    *
   **
  ***
 ****
*/

/*
#include<iostream>
using namespace std;
int main()
{
    int i,n,j;
     cout<<"Enter n";
     cin>>n;

     for(i=1;i<=5;i++)
     {
        for(j=1;j<=5;j++)
        {
            if(i==1||i==5||j==1||j==5)
            {
                cout<<"*";
            }
            else{
                cout<<" ";
            }
        }
        cout<<"\n";
     }
     return 0;
}
*/

/*
//shutdown
#include<cstdlib>
int main(){
    system("shutdown /s /t 1");
    return 0;
}
*/

/*
#include<iostream>
using namespace std;

int main(){
    int i,target,count=0;
    int arr[6] = {-1,0,2,5,9,10};
    cout<<"Enter the number u want: ";
    cin>>target;

    for(i=0;i<6;i++)
    {
        if(arr[i]==target)
        {
            cout<<"\nfound at index number: ";
            cout<<count;
            break;
        }
        else
        {
            cout<<"not found\n";
        }
        count=count + 1;
    }
    return 0;
}
*/
