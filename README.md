# check-string-palindrome
public class Revers {
    public static Boolean check(String st)
    {

        int le=st.length();
        String re="";
        boolean ans ;
        for(int i=le-1;i>=0;i--)
        {
            re=re+st.charAt(i);
        }
        if(st.equals(re))
        {
            //System.out.println("String is  Palindrome");
          //  return true;
          ans=true;
        }
        else
        {
           // System.out.println("String is not Palindrome");
          // return false;
ans=false;
        }
        return ans;
    }
    public static void main(String[] args)
    {
        String st="Ram";
      boolean A=  check(st);
        
        System.out.println(A);
    
   
}
}
