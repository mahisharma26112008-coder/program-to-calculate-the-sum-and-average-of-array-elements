# program-to-calculate-the-sum-and-average-of-array-elements

#include<iostream>
  using namespace std;
    int main(){
        int n;
        cout<<"enter the size of array : "<<"\n";
        cin>>n;
        
        int arr[n];
        for(int i=0; i<n;i++){
            cout<<"enter the elements of array  "<<i+1<<"\n";
            cin>>arr[i];
        }
        
        
        cout<<"elements are : "<<"\n";
         for(int i=0;i<n;i++){
             cout<<arr[i]<<" ";
         }
         
         int sum=0;
        
         for(int i=0;i<n;i++){
             sum=sum+arr[i];
         }
         
          cout<<"sum of elements :"<<sum<<"\n";
         
         float average=float(sum)/n;
         cout<<"the average is : "<<average<<"\n";
         
        return 0;
    }
