![http://www.cs.cmu.edu/~yuchenz/pics/logo_smaller.png](http://www.cs.cmu.edu/~yuchenz/pics/logo_smaller.png)

**hmmpytk** is a generic HMM (Hidden Markov Model) toolkit implemented in Python. It's designed with the following principles in mind:
  * Observations and states can be **anything** (primitive types, objects, tuples ... )
  * Does not depend on any external packages
  * Achieve reasonable efficiency
  * All the numeric calculations are done in the log domain (prevent underflow)

As one may know, Python scripts aren't the fastest programs on earth, therefore this toolkit will not be able to compete with the C/C++ implementations of HMM in the aspect of absolute speed. However, due to the self-contained nature (doesn't depend on external packages), there are many use cases for this.

**To get started, please take a look at this [Tutorial](Tutorial.md)**

**To check out the code from git, please use:**
```
git clone https://code.google.com/p/hmmpytk/ 
```

This software is available under the new BSD license.