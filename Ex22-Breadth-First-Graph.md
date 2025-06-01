# Ex22 Breadth First Graph
## DATE: 23.04.2025
## AIM:
To write a printQueue C function of the given graph that is to be traversed in the breadth first manner.

![image](https://github.com/user-attachments/assets/f483f48c-6af0-4027-a993-01c108a50933)

## Algorithm
1. Start
2. Start from the front index of the queue.
3. If the queue is empty, print "Queue is empty".
4. Otherwise, print "Queue contains" and display all items from front to rear.
5. Return after printing the queue contents.
6. End  

## Program:
```
/*
Program to traverse graph using BFS
Developed by: SRIVATSAN V
RegisterNumber: 212223110053
*/
void printQueue(struct queue* q) { 
    int i=q->front;
    if(isEmpty(q))
        printf("Queue is empty");
    else
    {
        printf("Queue contains ");
        for(i=q->front;i<q->rear+1;i++)
            printf("%d ",q->items[i]);
    }
}
```

## Output:
![5b](https://github.com/user-attachments/assets/6ef0cc3d-b8bc-4fb3-8fa4-ccacb1dbf627)

## Result:
Thus, the code for the printQueue function of the following graph that is to be traversed in the breadth first manner is implemented successfully.
