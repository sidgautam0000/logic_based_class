import java.util.*;
public class hello{
    public static String[] split(String a){
        if(a.equals("")||a==null){
            return new String[0];
        }
        String[] words=a.split(" ");
        return words;
    }
    public static void main(String[] args){
        Scanner sid=new Scanner(System.in);
        String c=sid.nextLine();
        c=c.toUpperCase();
        String[] words=split(c);int r=0,y=0,z=0;
        for(int i=0;i<words.length;i++){
            char[] b=words[i].toCharArray();
            int l=b.length-1,sum=0;
            if(b.length%2==0){r=b.length/2;}
            else{r=(b.length/2)+1;}
            for(int j=0;j<r;j++){
                y=b[j]-64;
                z=b[l]-64;
                int t=y-z;
                if(t<0){t=t*(-1);}
                if(y!=z){
                sum=sum+t;
                }
                else{
                sum=sum+y;
                }
                l-=1;
            }
            System.out.print(sum);
        }
    }    
}
