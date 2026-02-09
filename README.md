# DSA-CODE-
day 0 to here 

class Solution {
    public int[] twoSum(int[] nums, int target) {
       int[] arr=new int [2];
       
       for (int i=0;i<nums.length;i++)
       {
        for (int j=1+0;j<nums.length;j++)
        {
            if (nums[i]+nums[j]==target)
            {
                arr[0]=i;
                arr[1]=j;
                return arr;          
            }
        }
       }
       return arr;
    }
}
