# first-demo
This is my first GIT Repository
<br>
Author - Krishna Awasthi
<br>
<br>
// A Simple and Beginner Level C# Program :)
<br>

    #include<stdio.h>  
    int main() {
    int i, j, n;
    printf("Enter the number of rows: ");
    scanf("%d", &n);
    for (i = 1; i <= n; i++) {
        for (j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
     }

    return 0;  
    }
