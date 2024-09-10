class Solution {
public:
    Node* constructLL(vector<int>& arr) {
        // Step 1: Initialize the head node with the first element of the array
        Node* head = new Node(arr[0]); // Create a new node for the head
        Node* mover = head; // Initialize the mover to track the current end of the list

        // Step 2: Loop through the array starting from the second element
        for (int i = 1; i < arr.size(); i++) {
            Node* temp = new Node(arr[i]); // Create a new node for the current array element
            mover->next = temp; // Link the current end of the list to the new node
            mover = temp; // Move the mover to the new end of the list
        }

        // Step 3: Return the head of the linked list
        return head;
    }
};
