Lecture24- Strings Pt. 3
package strings;
public class StringStudy{
public static void main(Strings[] args){
        String name = "CipherSchool";
        String name2 = "CipherSchool";
    String name3 = new String("CipherSchools");
    String name4 = new String("CipherSchools");
    System.out.println(name == name 2);
    System.out.println(name3 == name 4);
    System.out.println(name == name 3);
String s1 = "Hello";
String s1 = s1+ "Peeps";
System.out.println(s1);
System.out.println(s1 + " How're you doing");
System.out.println(s1);


/////ANOTHER WAY 
String s2 = new String("Hello");
String s3 = new String("People");
String s4 = s2.concat(s3);
System.out.println(s2);
System.out.println("=======================================")
System.out.println("1. CONCATENATION");
String s1 = "Hello";
String s2 = "Peeps";
System.out.println(s1);
System.out.println(s1 + "How're you doing");
System.out.println(s1);
String s1 = "Hello";
String s2 = "Peeps";
s2.concat(s3);
System.out.println(s4);
System.out.println(s2);






System.out.println("==============================");
System.out.println("7. Length of a String");
int len = name.length();
System.out.println("Length:" +name+ "is:" + len);
System.out.println("==============================");
System.out.println("8. Finding index of a char in a String");
int index = name indexOf('e');
System.out.println("Index of 'e' in "+name+" is:" +index);


int index2 = name.indexOf('E');
System.out.println("Index of 'E' in " + name+  "is: + index2);

int index3 = name.indexOf('School');
System.out.println("Index of 'School' in " + name+  "is: + index3);

int index4 = name.indexOf('o', 10);
System.out.println("Index of 'o' in " + name+  "is: + index4);


while()
{
        indexOfO = name.indexOf('o', indexOfO + 1);
        if(indexOfO == 1) break;
        System.out.println("O found at: " + indexOfO);
System.out.println("=========================");
System.out.printn("9.Extract a Substring");
String wF = "Wakanda Forever"
String substring = wF.substring(3);
System.out.println(substring);
String substring2 = wF.substring(3,6);
System.out.println(substring);


System.out.println("=========================");
System.out.println("10.Finding a Character at a given index");
System.out.println(name.charAt(4));
int charAt Index = name.charAt(6);
System.out.println(charAtIndex);

System.out.println("=========================");
System.out.println("11. Array from a string ");
char arr[] = name.toCharArray();
for(int i = 0; i<arr2.length;i++{
{
System.out.println(arr 2 [i];
System.out.println("12. Check if a string is empty");
String emptyString = new String();
String emptyString 2 = " ";

System.out.println(emptyString 2);
System.out.println(emptyString.equals(" "));
System.out.println(emptyString2.equals(" "));
System.out.println(emptyString.isEmpty());
System.out.println(BlankString.isEmpty());pSystem.out.println(emptytring.isBlank());

System.out.println("=========================");
System.out.println("13. Comparing String lexicographically ->alphabetically");
String textOne = "QHey";
String textTwo = "QBye";

System.out.println(textOne.compareTo(textTwo));
System.out.println(textTwo.comapreTo(textOne));
System.out.println(textOne.comapreTo(textOne));

System.out.println("=====================");
System.out.println("14.Trimming white spaces from front and end");
String s5 = new String("Hello);
System.out.println();
System.out.println("Hello     ");
System.out.println(" Hello        ");
System.out.println( " Hello  People");
System.out.println( s5.trim());
System.out.println(s6.trim));
System.out.println(s7.trim));
System.out.println( "*" + s5.trim() + "*");
System.out.println( "*" + s6.trim() + "*");
System.out.println( "*" + s7.trim() + "*");
}
}
System.out.println("=====================");
System.out.println("15.Replacing a character ");
System.out.println(name.replace('o' , 'o');
System.out.println(name.replace("o" , "oooooooooooooo");
sc.close();
