public class Random {
   /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
  String[] szamok = {"23","15","54","78","44","80","72"};
  int length = szamok.length;
  for (int i=0; i< 5; i++)
  {
      int rand = (int) (Math.random() * length);  
      
  System.out.print(szamok[rand]);
  System.out.print( " ");
          
    }  
          
  }
}
