# 8 - Perfect Squares
This problem requires us to fnd the smalles number of additions of perfect square to add up to n. Basicaly we want to start with n. At n we have a certain number of options to subtract from n. the options we can choose from are all the perfect squares from 1 to the last perfect square that is ness than n. What we would want to probably do is first subtract the highest number from our list of options from n. we would then have a new n with a new list of options to choose from and again we would do the same doing this recursively until we reach zero. We wold then save the number of steps it took to reach 0 picking each option and returning the smallest number of steps. The goal at each step would be to find what are the smallest number of steps we can take from that number to 0.


In order to do this  dynamically I would probably have a dictionary that stored the number of steps determined to be the shortest after checking all the options at each subvalue of n. That way we can check if the current value of n is in the dictionary. if it is then we dont need to waste time checking each of the optionsand we can return that value. if it isnt then we go down each option and once we know what the value is we add it to the dictionary for the next time it comes up.

I wasnt able to implement this soluton unfortunately. no time
