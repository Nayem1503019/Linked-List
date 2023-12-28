# Linked-List
### To reverse a linked list : a-->b-->c-->d-->null
node curr=head;</br>
node prev=null;
at first curr holds node a(head), prev is null.
1. Save the node b at a temporary node i.e temp  =>  node temp=curr->next. it will save node b .otherwise we will lost the connection to b. curr->next is a pointer to node b.
2. Break the link (a-->b) : curr->next=prev . node a now points to null
3. prev=curr, prev holds node a
4. curr=temp . now curr points to node b

prev->curr->temp
