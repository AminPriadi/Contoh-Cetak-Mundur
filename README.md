# Contoh-Tukar-Array
    #include<stdio.h>

    void tukar(int array[2])
    {
        int t=array[0];
        array[0]=array[1];
        array[1]=t;
    }
    int main(A){
    int array[2]={1,2};
    printf("before %d-%d\n",array[0],array[1]);
    tukar(array);
    printf("after %d-%d",array[0],array[1]);
    }
   # Hasil
   ![img](https://raw.githubusercontent.com/AminPriadi/Contoh-Cetak-Mundur/master/9.png)
