# TestVagrant
Assessment

public class SongPlaylist 
{
	
 static String [] a = {"Song S1 played","Song S2 played","Song S3 played","Song S4 played"};

 public static void Playlist()
 {
  System.out.println("Playlist played-->");
  for(int i=0; i<3; i++)
  {
   System.out.println(a[i]);
  }
 }
	
 public static void Song4Played(String x)
 {
  System.out.println("When Song 4 played-->");
  if(x.equals("S4"))
  {
   System.out.println(a[1]);
   System.out.println(a[2]);
   System.out.println(a[3]);
  }
 }
 public static void Song2Played(String y)
 {
  System.out.println("When Song 2 played-->");
  if(y.equals("S2"))
  {
   System.out.println(a[2]);
   System.out.println(a[3]);
   System.out.println(a[1]);
  }
 }
 public static void Song1Played(String z)
 {
  System.out.println("When Song 1 played-->");
  if(z.equals("S1"))
  {
   System.out.println(a[3]);
   System.out.println(a[1]);
   System.out.println(a[0]);
  }
 }
	
public static void main(String[] args) {
	
 Playlist();
 Song4Played("S4");
 Song2Played("S2");
 Song1Played("S1");
	
}
}
