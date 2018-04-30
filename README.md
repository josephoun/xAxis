# Dynamic xAxis Bar with Zoom In and Zoom Out

I have created an xAxis bar. 

You can define everything in the constants section, including how many ticks in the chart, what is the range between every tick in pixels, zoom in and zoom out limits and what is the jump value between every tick.

After you define these constants everything is generated using native JavaScript. 

```
        // define how much pixels between every tick
        PIXELS_BETWEEN_TICKS
		
        //define minimum pixels between every tick to limit the zoom in
        MINIMUM_PIXELS_BETWEEN_TICKS
		
        //define maximum pixels between every tick to limit the zoom out
        MAXIMUM_PIXELS_BETWEEN_TICKS
		
        //define how much ticks in the chart
        TICKS_NUMBER
		
        //define the jump range (the numeric value jump from tick to tick)
        TICK_VALUE_JUMPING
```

		
All the code is commented and should be easy to read.
 
Enjoy!