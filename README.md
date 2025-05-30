# Thoughts
This problem was conceptually easy, however, the edge cases kept up screwing up my algorithm. Eventually, I had realized my mistake and not accounted for when there are only two
elements in the list. I knew immediately that this was a bThe way my algorthim works is that in order to find element 'n' in a rotated sorted array, I first check if the first element is less than the middle element, then
I have a nested if statement that additionally checks if the target number is inbetween this range, if it is, we cut off the right side of the middle element, else, we cut off the left
side. In addition to this, I have an additionaly nested if statement that checks if the middle value is less than the last value in the list and that the target number is inbetween
this range, if so, we remove all the values to the left of the middle value, if not, we cut all the values to the right of the middle value. These are iterated continously until
left <= right for our left and right pointers set in a default binary search algorithm and the middle value is also updated PRIOR to checking all of the if statements in the while loop.
