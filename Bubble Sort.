public class Solution {
    public static void main(String args[] ) throws Exception {
        Scanner sc=new Scanner(System.in);
        int[] nums=new int[10];
        for(int i=0;i<10;i++){
            nums[i]=sc.nextInt();
        }
        int i=0;
        while(i<=10){
            for(int j=0;j<10-i-1;j++){
                if(nums[j]>nums[j+1]){
                    int temp=nums[j];
                    nums[j]=nums[j+1];
                    nums[j+1]=temp;
                }
            }
            i++;
        }
        for(int k=0;k<nums.length;k++){
            System.out.print(nums[k]);
            System.out.print(" ");
        } 
    }
}
