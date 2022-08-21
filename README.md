# gemini_unit2_task4_prob5

import java.util.LinkedList; import java.util.Queue;

public class QueueExample {

public static void main(String[] args)
{
    Queue<Integer> q
        = new LinkedList<>();

    
    
    for (int i = 0; i < 7; i++)
      q.add(i);

   

    // To remove the head of queue.
    int removedele = q.remove();
    System.out.println("removed element-"+ removedele);

    System.out.println(q);

    // To view the head of queue
    int head = q.peek();
    System.out.println("head of queue-"+ head);


    int size = q.size();
    System.out.println("Size of queue-"
                       + size);
}
}
