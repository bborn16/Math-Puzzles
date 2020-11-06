assume that you are number 0.
people are numbered 0 through 60.

## round 1:
the first player to be eliminated is #18. 
hence n % 61 = 19

## round 2:
play starts with #19, and #50 is eliminated.
hence n % 60 = 32

## round 3:
play starts with #51, and #51 is eliminated.
hence n % 59 = 1

effectively, this question asks what is the smallest n s.t. n % 61 = 18, n % 60 = 31, and n % 59 = 0.

this gives us a system with 3 equations and 4 variables, as shown below.
k1*61 + 19 = n
k2*60 + 32 = n
k3*59 + 1 = n

we can then solve this iteratively, and we get that the solution is 136232.

## program
public class HotPumpkin{

     public static void main(String []args){
        int n = 0;
        while (!(n % 61 == 19 && n % 60 == 32 && n % 59 == 1)) {
            ++n;
        }
        System.out.println(n);
     }
}
