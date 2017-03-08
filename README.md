# overdride
overdride
answer is option:3
No, a private method cannot be overridden since it is not visible from any other class. You have declared a new method for your subclass that has no relation to the superclass method. One way to look at it is  whether it would be legal to write super.func() in the Derived class. There is no way an overriding method would be banned from accessing the method it is overriding, but this would precisely be the case here.
and it prints: Parent's method2()
               Parent's method1()


