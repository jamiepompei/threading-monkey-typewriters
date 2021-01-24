# Threading Practice: Monkeys Typewriters


### Part 1

The abstract base class of `Copier` has a constructor that takes a String and turns that into an iterator so we can traverse the text to be copied 
and pass it along to each monkey (thread).

`UnsafeCopier` extends `Copier`. The `run` method that will have the monkey grab the next word and append it to the copy.

`MonkeyTypewriter` creates 5 monkeys (threads) using the `UnsafeCopier`.

After the sleep, print out the results of the unsafely copied passage.

### Part 2

Finish the `SafeCopier` and then call that from the main method, in addition to the unsafe version.

