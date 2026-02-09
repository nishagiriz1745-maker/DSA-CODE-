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


#given integer and we need to find the correct ouput 
the function which we follow is arry 
given no. of integer [2,7,11,15]
output=9
method we use to find it is 
0,1,2,3 
i,j 
int i =0;
int = 1+1;

so 2+7 =9 break; 
2+11 =/ 9 
2+15=/ 9 

as we need to search for the output so we need to provide a array lengthe which will be 
i>nums.lengths; or j>nums.lengths which indicate it will calculate till 3 array which is 15. 

so will use this function till the point we didnt get the target once we get the target we will break the function . 
