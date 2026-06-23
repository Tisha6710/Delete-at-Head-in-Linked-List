# Delete-at-Head-in-Linked-List
class LinkedList {

    static class Node {
        int data;
        Node next;

        Node(int data) {
            this.data = data;
        }
    }

    Node head = null;

    // 👉 delete at head
    void deleteAtHead() {
        if (head == null) {
            System.out.println("List is empty");
            return;
        }

        head = head.next;  // ⭐ main logic
    }
}
