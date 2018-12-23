# Membuat fungsi untuk menyederhanakan b/c Ab/c


Coding program lengkap

    #include <stdio.h>

    int pecahan ();
    int main (){
    pecahan();
    }

    int pecahan()
    {
     int a,b,l,t;
     printf ("Masukan pembilang = ");
     scanf ("%d",&a);
     printf ("Masukan penyebut = ");
     scanf ("%d",&b);
     t=a/b;
     l=a%b;
     if (a%b == 0)
        printf ("Bilangan (%d/%d)\n di sederhanakan menjadi %d",a,b,t);
     else if (a%b != 0)
        printf ("Bilangan (%d/%d \n di sederhanakan menjadi (%d %d/%d)",a,b,t,l,b);

    }


Hasil program

![img](https://raw.githubusercontent.com/MUTIARAIZMI/Membuat-fungsi-untuk-menyederhanakan-b-c-Ab-c/master/menyederhanakan%20pecahan.jpg)
