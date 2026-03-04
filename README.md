# Linked-List-2-DS
Practice program
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

def insertAtHead(head, value):
    newNode = Node(value)
    newNode.next = head
    return newNode   # new head

# Main
head = None   # empty list

head = insertAtHead(head, 10)
head = insertAtHead(head, 20)
head = insertAtHead(head, 30)

# Print list
temp = head
while temp:
    print(temp.data)
    temp = temp.next
Output:
30
20
10
    
