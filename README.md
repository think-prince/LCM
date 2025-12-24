# LCM
Code for LeastCommonMultiple
public class LeastCommonFactor {
    public static int LCM (int x, int y){
        int i =1; int fact=0;
        while (i<=y){
             fact = x*i;
            if(fact%y==0){
                return fact;
            }  i++;
        }
        return fact;
    }
}
