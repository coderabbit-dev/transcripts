# Thinking Like a Computer
In order to write instructions that we want a computer to run, we need to understand a little bit more about how computers "think." Of course, computers aren't able to reason through a situation like a human might, so that means the thinking is our job.
It should help to visualize programming as moving from some input, like five different numbers, to an output, like the average of those numbers. We can think through the steps it takes to calculate an average, so we simply have to pass along those instructions to the computer. That's really all code is!

In plain English, we add the numbers together, then divide the sum by how many numbers there are, and we have an average.
Let's write it out. 12 + 8 + 9 + 27 + 19

Input ---> Output

## Morning Routine
Let's say you want to program your morning routine. This is obviously a bit more complex than calculating an average, so we're going to walk through it.

Your alarm goes off. 
If you aren't running late for work, you might hit the snooze once. Loop back to top.
Otherwise, if you are on time
    you'll wake up
    take a shower
    get dressed
    have breakfast
    brush your teeth
    get in your car and drive the speed limit to work
Otherwise, if you're late
    you'll wake up
    get dressed
    brush your teeth
    get in your car and speed to work
 
 We can look at this situation as a series of events that branch off, sort of like a tree. This is how we might start to formulate a "program" for our morning routine.


 alarmBuzz();
 if (timeLeft > 45) {

 } else if (timeLeft < 45 && timeLeft > 20) {
     wakeUp();
 } else {
     wakeUp();
 }