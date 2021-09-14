public class Multiplicationofarray
{
    public static  void main(String[]args)
    {
        int[]arr=new int[]{9,4,8,6,1};
        int multiplication=0;
            for(int i=0;i<arr.length;i++) {
         multiplication=multiplication+arr[i];
          }
         System.out.println("Multiplication of all the elements of an array:"+multiplication);
    }
}
