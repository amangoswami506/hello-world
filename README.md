public class factorial{
public static void main(String args[]){
System.out.print(factor(30));
}
static int factor(int n){
int fact=1;
for(int i=1;i<=n;i++){
fact*=i;
}
return fact;
}
}
