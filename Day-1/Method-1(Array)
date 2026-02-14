class Solution {
    static final int x=30000;
    public int singleNumber(int[] nums){
        int count[]=new int[100001];
        for(int i:nums)
            count[i+x]++;

        for(int i=0;i<=100000;i++){
            if(count[i]==1) 
                return i-x;
        }
        return -1;
    }
}
