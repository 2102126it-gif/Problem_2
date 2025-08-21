 import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.util.*;
class TestClass {
    public static void main(String args[] ) throws Exception {
        //BufferedReader
        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
        int n=Integer.parseInt(br.readLine().trim());
        String[] parts = br.readLine().trim().split(" ");
        int last = Integer.parseInt(parts[n-1]);
        if(last%10==0){
            System.out.println("yes");
        }
        else{
            System.out.println("No");
        }
    }
}

