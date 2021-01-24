# Threading Practice Monkeys Typewriters

## Monkey Typewriter
According to Wikipedia:

> The infinite monkey theorem states that a monkey hitting keys at random on a typewriter keyboard for an infinite 
amount of time will almost surely type a given text.

We don't have that kind of time, but what we do have are super smart monkeys.  These monkeys are able to copy text.

So, guess what.  We're starting a printing company powered entirely off of monkey typists.


### Part 1

The abstract base class of `Copier`  has a constructor that takes a String and turns that into an iterator so we can traverse the text to be copied and pass it along to each monkey (thread).

Extend `Copier` in `UnsafeCopier`.  Then, write a `run` method that will have the monkey grab the next word and append
it to the copy.

Modify `MonkeyTypewriter` to create 5 monkeys (threads) using the `UnsafeCopier` and start them.

After the sleep, print out the results of the unsafely copied passage.

### Part 2

Finish the `SafeCopier` and then call that from the main method, in addition to the unsafe version.




