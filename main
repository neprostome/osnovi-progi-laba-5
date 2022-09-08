#include <stdio.h>

int main() {
    int a[7] = {0, 3, 5, 7, 11, 13};
    for(int i = 0; i < 7; i++){
        printf("%d ", a[i]);
    }
    printf("\n");
    int x[2][2] = {1, 0, 1, 4};
    int y[2][2] = {1, 2, 0, 1};
    int z[2][2] = {(x[0][0] * y[0][0]) + (x[0][1] * y[1][0]), (x[0][0] * y[0][1]) + (x[0][1] * y[1][1]),
                   (x[1][0] * y[0][0]) + (x[1][1] * y[1][0]), (x[1][0] * y[0][1]) + (x[1][1] * y[1][1])};
    for(int i = 0; i < 2; i++){
        printf("%d ", z[0][i]);
    }
    printf("\n");
    for(int i = 0; i < 2; i++){
        printf("%d ", z[i][0]);
    }
    return 0;
}
