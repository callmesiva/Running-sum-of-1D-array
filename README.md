# Running-sum-of-1D-array
# method 1

    int nums[] ={1,1,1,1,1};
    int sum=0;
     
     for(int i=0;i<nums.length;i++)
      {
        sum+=nums[i];
        nums[i]=sum;
       }
     
    for(int i=0;i<nums.length;i++)
         {
            System.out.println(nums[i]);  //Ans 1 2 3 4 5
           }
 
# method 2

   int nums[] = {1,1,1,1,1};
   
     for(int i=1;i<arr.length; i++)
        {
          arr[i] =  arr[i]+ arr[i-1];
        }
        
     for(int i=0; i<arr.length; i++)
        {
            System.out.println(arr[i]); //Ans 1 2 3 4 5
          }
