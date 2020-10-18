package com.programArray;
import java.util.Scanner;

public class Main {

    public static void Main(String[] args) {
	// write your code here
        Scanner input = new Scanner(System.in);

        int data[][];
        //data = new int[2][5];
        System.out.print("\nProgram Pendeteksi Bilangan Prima");
        System.out.print("\nMasukkan Baris ");
        int inputan = input.nextInt();
        System.out.println("\nMasukan Kolom");
        int kolom = input.nextInt();
        data = new int[kolom][inputan];

        //int a = 0;
        //if(a < inputan){
        //a++;
        System.out.println();
        for (int i = 0; i < inputan; i++) {
            for(int a = 0; a< kolom; a++){
                System.out.print("\nMasukkan bilangan bulat positif: ");
                int angka = input.nextInt();
                data[a][i] = angka;
            }
        }
        for (int i = 0; i < inputan; i++) {
            System.out.print("| ");
            for(int a = 0; a< kolom; a++){
                System.out.print(data[a][i] + " ");
            }
            System.out.println("|");
        }
        //}
        for (int i = 0; i < inputan; i++) {
            for(int a=0; a < kolom; a++){
                    int bil=0;
                    for (int j=1;j<=data[a][i];j++){
                        if (data[a][i]%j==0){
                            bil=bil+1;
                        }
                    }
                    if (bil==2) {
                        System.out.print(data[a][i] + " = Bilangan Prima ");
                    }else {
                        System.out.print(data[a][i] + " = Bukan Bilangan Prima ");
                    }
                }
            }
        }
    }

