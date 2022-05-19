class Main {
  static void sumofallDigits(int a)
  {
    String str = Integer.toString(a);
    int size = str.length();
    int sum = 0;
    int[] array = new int[size];
    for(int i=0; i<size; i++)
      {
        if(i ==0 )
        {
          array[i] = a%((int)Math.pow(10, i+1));
        }
        else  
        {
          array[i] = (a%((int)Math.pow(10, i+1)))/((int)Math.pow(10, i));
        }
        sum += array[i];
        // System.out.println(array[i]);
      }
    System.out.println(sum);
  }
  
  public static void main(String[] args) 
  {
    sumofallDigits(123);
  }
}
