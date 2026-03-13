# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to print all elements in an array that are greater than a given value



## AIM:
To write a Java program to print all elements in an array that are greater than a given value

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read n (size of array).
4. Read n elements into the array.
5. Read value val.
6. Check each element of the array:
      If element > val, print it.
7. If no element is greater than val, print "No elements greater than val".
8. Stop.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: S KANUSHA SREE
RegisterNumber:  212224040149
*/
```

## SOURCE CODE:
```
import java.util.*;
public class main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int arr[]=new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        boolean iss=false;
        int val=sc.nextInt();
        for(int i=0;i<n;i++){
            if(arr[i]>val) {
                System.out.println(arr[i]);
                iss=true;
            }
        }
        if(!iss) System.out.print("No elements greater than "+val);
    }
}
```
## OUTPUT:
<img width="1211" height="708" alt="image" src="https://github.com/user-attachments/assets/88afdbfe-6c6b-4e0e-8a1e-27788edda5cf" />

## RESULT:
Thus the program is successfully executed.

