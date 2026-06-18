import java.util.*;
public class Anagram_Frequency {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		String s1= sc.next();
		String s2 = sc.next();
		int[] f= new int[26];
		
		for(char c : s1.toCharArray()) {
			f[c -'a']++;
		}
		for(char c: s2.toCharArray()) {
			f[c - 'a']--;
		}
		int sp =0;
		for(int i=0;i<26;i++) {
			sp += Math.abs(f[i]);
		}
		System.out.println(sp);
	}

}
