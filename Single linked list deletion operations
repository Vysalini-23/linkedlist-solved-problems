class Node:
    def __init__(self,data):
        self.data=data
        self.next=None
class Sll:
    def __init__(self):
        self.head=None
    def display(self):
        if self.head==None:
            print("SLL is empty")
        else:
            temp=self.head
            while temp is not None:
                print(temp.data,"-->",end=" ")
                temp=temp.next 
    def delete_first(self):
        temp=self.head
        self.head=temp.next
        temp.next=None
    def delete_last(self):
        temp=self.head.next
        prev=self.head
        while temp.next is not None:
            temp=temp.next
            prev=prev.next
        prev.next=None
    def delete_pos(self,pos):
        temp=self.head.next
        prev=self.head
        for i in range(pos-1):
            temp=temp.next
            prev=prev.next
        prev.next=temp.next
        temp.next=None
l=Sll()
n=Node(10)
l.head=n 
n1=Node(20)
n.next=n1
n2=Node(30)
n1.next=n2
n3=Node(40)
n2.next=n3
#l.delete_first()
#l.delete_last()
#l.delete_pos(1)
l.display()
    
