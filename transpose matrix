#include<stdio.h>  
int main(){  
    int m, n;  
    printf("Enter the number of rows: ");  
    scanf("%d", &m);  
    printf("Enter the number of columns: ");  
    scanf("%d", &n);  
    int matrix[10^5][10^5];  
    printf("Enter the elements of the matrix:\n");  
    for(int i=0; i<m; i++){  
        for(int j=0; j<n; j++){  
            scanf("%d", &matrix[i][j]);  
        }  
    }  
    for(int i=0; i<m; i++){  
        for(int j=0; j<n; j++){  
            int temp = matrix[i][j];  
            matrix[i][j] = matrix[j][i];  
            matrix[j][i] = temp;  
        }  
    }  
    printf("The transposed matrix is:\n");  
    for(int i=0; i<n; i++){  
        for(int j=0; j<m; j++){  
            printf("%d ", matrix[i][j]);  
        }  
        printf("\n");  
    }  
    return 0;  
}  
