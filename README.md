# find-max-and-minimum-values-among-the-given-10-numbers
public class Arrays {
	public static void main(String[] args) {
		int[]arr1={1,4,34,56,7};
		 int len1=arr1.length;
		 int key=Integer.parseInt(args[0]);
		 for(int i=0;i<len1;i++)
		 {
			 if (key==arr1[i])
			 {
				 System.out.println("Position of key element"+(i+1));
				 break;
			 }
			 else
			 {
				 System.out.println(-1);
				 
			 }
			 
		
		 }
		


}
}
