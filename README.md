<h1>Assignment 2: Analog Clock</h1>

<h2>Introduction</h2>
<p>
  The subject of my assignment is the Analog Clock Widget. The widget displays the hour and minute in a analog clock format with two hands. The background colour can be changed for the AnalogClock view. The widget can be embedded in to an activity/fragment as a more decorative way to display time. There is not hand for keeping track of seconds and there are no labeled numbers on the clock face.
</p>

<img src="analog_clock_example.png" alt="Analog Clock Example"/>

<h2>History</h2>
<p>
  The AnalogClock widget was first released with Android API level 1 in October 2008 and was deprecated with API level 23 on October 25. The widget belongs to the android.widget library at android.widget.AnalogClock. 
  The widget was largely unchanged since being launched with the original version of Android, with the exception of the addition of a new contructor in API level 21:
  
  public AnalogClock (Context context, 
                AttributeSet attrs, 
                int defStyleAttr, 
                int defStyleRes)
  
</p>

<h2>Methods & Attributes</h2>
<p>
  
 There are no methods required for the functionality of the AnalogClock, but there are View functions for modifying attributes and for dealing with changing canvas size. There are 3 attributes. android:dial, android:hand_hour and android:hand_minute.
 
 The android:dial attribute can be used to supply and image that will be rendered as the clock face. The android:hand_hour and android:hand_minute attributes can be used to suppy and image for a custom hour and minute hand respectively.
 
There are four constructors for the AnalogClock view:
  
  <b>public AnalogClock (Context context)</b>
  
  <b>public AnalogClock (Context context, 
                AttributeSet attrs)</b>
  
  <b>public AnalogClock (Context context, 
                AttributeSet attrs, 
                int defStyleAttr)</b>
                
  <b>public AnalogClock (Context context, 
                AttributeSet attrs, 
                int defStyleAttr, 
                int defStyleRes)</b>
                
                
four protected methods:

  <b>void onAttachedToWindow ()</b>
  
  <b>void onDetachedFromWindow ()</b>
  
  <b>void onDraw (Canvas canvas)</b>
  
  <b>void onMeasure (int widthMeasureSpec, 
                int heightMeasureSpec)</b>
                

</p>



<h2>Sample Code</h2>
<p>

</p>


<h2>References</h2>
<ol>
  <li>https://developer.android.com/reference/android/widget/AnalogClock</li>
</ol>


