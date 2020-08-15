
# AIM OF THE EXPERIMENT:  To write a binary search program using recursive function.
BINARY SEARCH : to find a key element in an given array in which the elements must be sorted.
# PROCEDURE :
First we to take an array i.e. p[] = {3,12,29,33,36,54,60,61,92,98}
Consider a  variable to iterate the elements in array i.e. ”s” and also find the mid value i.e. mid =(0+n)/2 or (first + last)/2, where n is index of last element.
Now iterate the loop i.e.  for (s=0; s<=n; s++)
Case 1: Then if the key element is equal to mid value print “I” this is the position of key element.
Case 2 :If the mid value is greater than key element than first = mid -1
Case 3: If the mid value is less than key element than first = mid +1

This will be continued until key element is found or until search space exhausted.
INPUT :
           12
                  92
                   33
OUTPUT:
               1
                8
               4
     
![binary recurscive 1](https://user-images.githubusercontent.com/69640871/90316777-2d5b1180-df42-11ea-989f-f5dad5a67580.png)
![binary recursive 3](https://user-images.githubusercontent.com/69640871/90316799-5085c100-df42-11ea-9be7-af095ba2f323.png
)
![binar recursive 2](https://user-images.githubusercontent.com/69640871/90316768-1ddbc880-df42-11ea-97f5-e1e0e9cbe5a8.png)
