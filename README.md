# inheritence
class base1:
    def getdata(self,i,j):
        self.i=j
        self.j=j
        def display1(self):
            print("i=",self):
            print("j"=,self):
class base2:
                  class derived(base1, base2):
    def getdata3(self,i,j,a,b,m):
        base1.getdata1(self,i,j)
        base2.getdata(self,a,b)
        self.m=m
    def display3(self):
        base1.display1(self)
        base2.display2(self)
        print("m=",self.m)
       

d1 = derived()
d1.getdata3(1,2,3,4,5)
d1.display3()
