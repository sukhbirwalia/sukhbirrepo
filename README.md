# sukhbirrepo


package interviewQues;

public class reverseArray {

	public static void main(String[] args) {
		
		int i[] = new int[4];
		i[0]=100;
		i[1]=200;
		i[2]=300;
		i[3]=400;
		
		System.out.println(i.length);
		
		for(int x=0; x<i.length; x++){
			System.out.println(i[x]);
		}
		
		for(int x=i.length-1; x>=0; x--){ // reverse array
			System.out.println(i[x]);
		}
	}

}
