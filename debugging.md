# CP01 - Debugging
### Independent debugging
In the tdd-bowling-kata I encountered an issue where I wasn't able to count the perfect game correctly. Somewhere in my dog's breakfast I was trying to access an undefined value.

First I tried things by adding conditions into my if statements to see if that was able to solve the issue. After a bit of frustration, I decided to slow down and methodically `console.log` my results and managed to find where the undefined was trying to be accessed and was able to code out a solution fairly quickly from there.

### Collaborative debugging
This morning when working through the kata-typescript challenge at the `findLongestWord` problem we gave it a crack trying to wiggle our way through with `for` loops but weren't seeing any success.

We stopped to talk about the problem and sift through possible solutions through this it was suggested that we use `.sort`. After taking a look at the docs and googling to see how people used it to sort arrays by string length we arrived at a solution fairly quickly after that.