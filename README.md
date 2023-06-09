# Queue-using-Array
<b><ins>To implement a queue using an array,</b></ins><br>
1.create an array arr of size n and 
take two variables front and rear both of which will be initialized to 0 which means the queue is currently empty.<br>
2.Element <br>
3.rear is the index up to which the elements are stored in the array and  <br>
4.front is the index of the first element of the array. <br> 
<br>
 Now, some of the implementations of queue operations are as follows:<br>
<b><ins>Enqueue:</b></ins> Addition of an element to the queue. Adding an element will be performed after checking whether the queue is full or not. If rear < n which indicates that the array is not full then store the element at arr[rear] and increment rear by 1 but if rear == n then it is said to be an Overflow condition as the array is full.<br>
<b><ins>Dequeue:</b></ins> Removal of an element from the queue. An element can only be deleted when there is at least an element to delete i.e. rear > 0. Now, the element at arr[front] can be deleted but all the remaining elements have to shift to the left by one position in order for the dequeue operation to delete the second element from the left on another dequeue operation.<br>
<b><ins>Front:</b></ins> Get the front element from the queue i.e. arr[front] if the queue is not empty.<br>
<b><ins>Display:</b></ins> Print all elements of the queue. If the queue is non-empty, traverse and print all the elements from the index front to rear.<br>
![image](https://user-images.githubusercontent.com/124968304/234173239-9b9e5faf-1abd-4e3b-96ae-25d3157c1363.png)<br>
<br>
<b><ins>Output</b></ins><br>
<img width="599" alt="Queue using array" src="https://user-images.githubusercontent.com/124968304/234174335-054ac4ef-8089-4d7d-a9d7-3bb24d72702d.png">




