# list.java
import java.util.*;
class average
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
ArrayList<Integer> al=new ArrayList<Integer>();
al.add(1);
al.add(2);
al.add(3);
al.add(4);
al.add(5);
al.stream().mapToInt(i -> i).average().ifPresent(avg -> System.out.println("AVERAGE OF NUMBERS IS"+" "+ avg));
}
}
