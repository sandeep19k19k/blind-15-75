# blind-15-75
Reverse bits

I guess conveyor belts analogy can explain this program .
Imagine we have 2 conveyor belts.
1) First one has Has 32 items, can move to right , when needed
2) Second one is Empty , not yet initialized, can move to left

The algo:
1) Initialize second conveyor belt, i.e move to left little bit, so that we can accomodate 1 item.
2) Pick 1 item from first conveyor belt and put it on the second conveyor belt.
3) update/ move conveyor belts. first one to the right and second one to the left.
4)Repeat this process until all items from the first conveyor belt all placed on the second conveyor belt.

Key aspects:
Usage of '&' and operator to find out the least significant bit in given number.
Usage of '|' or operator to update result variable .
Usage of right shift and left shift operator as and when needed appropriately,otherwise answer will get multiplied by 2 .

Time complexity: O(1)  bcoz size of integer in this case is constant 32 bits.
Space complexity: O(1)
