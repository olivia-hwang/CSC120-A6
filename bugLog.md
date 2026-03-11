## Bug 1
Brief description:  On line 15, the program creates a new array list for the inventory, but we have already included an inventory array list in the attributes of the class
Failed unit test: 

## Bug 2
Brief description: (ResaleShop.java) line 27 is redundant-- We take in a Computer object as an input but then create a new Computer object to add to the inventory.
Failed unit test: 

## Bug 3
Brief description:  
Failed unit test: (ResaleShop.java) The for loop in line 47 runs for one index too long. it should be "<"

## Bug 4
Brief description:  
Failed unit test: (ResaleShop.java) The for loop in line 47 is unnecessary. We only need to print one statement of the inventory

## Bug 5
Brief description: (ResaleShop.java) For lines 63-71, the for loop is rewriting the wrong values. For example, a Computer that was made in 1999 would be priced at 550, instead of 0, which is what was intended.
Failed unit test: 

## Bug 6
Brief description: (Computer.java) When initializing the Computer class, we assign this.memory = 16, which would overwrite whichever input for memory for the instance. 
Failed unit test: 

## Bug 7
Brief description: (Computer.java) When initializing the Computer class, we assign this.price = 0, which would overwrite whichever input for price for the instance. 
Failed unit test: 

## Bug 8
Brief description:  In line 51, using the method to set OS just automatically sets the OS to "none", regardless of what OS you choose.
Failed unit test: 

## Bug 9
Brief description: (ResaleShop.java) In lines 16-17, we add a new Computer object to the inventory as a part of the constructor so the inventory always contains one Computer object.
Failed unit test: 

## Bug 10
Brief description:  
Failed unit test: 