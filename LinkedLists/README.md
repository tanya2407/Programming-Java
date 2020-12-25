Defination for a node in singly Linked List:
```
public class ListNode {
      int val;
      ListNode next;
      ListNode() {}
      ListNode(int val) { this.val = val; }
     ListNode(int val, ListNode next) { this.val = val; this.next = next; }
 }
```
Create a new node: `n.next = new ListNode(val);`
