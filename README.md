class rectangle :

    def __init__(self,l1,b1):
        self.l1 = l1
        self.b1 = b1
        self.squ1 = self.square(12,13)

    def area1(self):
        return(self.l1 * self.b1)

    class square :

        def __init__(self,l2,b2):
            self.l2 = l2
            self.b2 = b2

        def area2(self):
            return (self.l2 * self.b2)




A1 = rectangle(12,10)
print(A1.area1())
print(rectangle.square.area2)
