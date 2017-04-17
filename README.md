# CharArrayManipulator
this readme.md is not complete

This Library is for less GC working char array manipulator

In Java ,String(immutable char array) sometimes is not good 

#for example In Game Loop, Update Game Score.

' String score ="Score:"+point;'

this code generally  is much as below

' String score =new StringBuilder().append(score).append(point);'

So Each Game Loop generate StringBuilder(). It make GC work more frequently.
Nowaday memory size is so much.
But Low Memory Device like a Android can prove latency.
I think This is so bad for Game Application.

If you use this Char Array Manipulator(Cam) ,Performance may be higher.

this is in progress so not complete.　
#Don't Miss This!!
