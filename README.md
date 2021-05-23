# LinkedList.py


Design a class named LinkedList with the follow methods:

__init__(self, node: Node) # initialize a linked list with it's head and tail

get_head(self) # return head node

get_tail(self) # return tail node

add(self, node: Node) # add a new node to tail with value

is_empty(self) # check if the LinkedList is empty

__str__(self) # return the string version of your linked list, for example, 1 -> 5 -> ...
 
You will need to define a class name Node as well:

__init__(self, value: int = 0) # initialize a node with integer

get_value(self) # return the value of the Node



n = Node()

l = LinkedList(n)

l.add(Node(1))

l.add(Node(2))

print(str(l))

print(l.is_empty())

print(l.get_head().get_value())

print(l.get_tail().get_value())

return 

0 -> 1 -> 2

False

0

2
