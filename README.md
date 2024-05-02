# Java---Arrays--Types--copyOf
import java.util.*;
class Main {
    public static void main(String[] args) {
        int a[]={72,56,9,76,1098};
        int b[]= Arrays.copyOf(a, 3);
        for(int temp:a){
            System.out.print(temp+" ");
        }
        System.out.println();
        for(int temp1:b){
            System.out.print(temp1+" ");
        }
    }
