## Inner Joins with optional Watermarking

```css
Inner joins on any kind of columns along with any kind of join conditions are supported. 
However, as the stream runs, the size of streaming state will keep growing indefinitely as all past input must be saved as any new input can match with any input from the past. 
To avoid unbounded state, you have to define additional join conditions such that indefinitely old inputs cannot match with future inputs and therefore can be cleared from the state. 
In other words, you will have to do the following additional steps in the join.

```
Inner joins是支持的。
然而，当流运行时，

