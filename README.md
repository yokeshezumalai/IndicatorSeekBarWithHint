# IndicatorSeekBarWithHint
A custom SeekBar on Android - Kotlin, will show hint view with progress above SeekBar when seeking.
A custom seek bar with floating textview

https://github.com/Yokeshthebouncer/IndicatorSeekBarWithHint

# Implementation

### Gradle Dependency

```
implementation 'com.github.Yokeshthebouncer:IndicatorSeekBarWithHint:1.1.1'
```

### Usage

```
<com.yokesh.indicatorseekbar.SeekBar
        android:id="@+id/numberOfChequeBooks"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="20dp"
        android:layout_marginEnd="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:startValue="0"
        app:maxValue="10"
        app:progressDrawable="@drawable/seekbar_progress_drawable"
        app:progressTextColor="@color/colorRedPrimary"
        app:thumb="@drawable/custom_thumb" />
```
       
       
User can customise the min and max value from the xml and they can also customise the progress text color and progress drawable. 

And also user can set the min and max value by using the method,
```
seekbar.setMinMax(min, max)
```

Set progress and get progress by 
```
seekBar.setProgress(1)
```
```
seekbar.getProgress()
- It will get you the progress using live data
```


A simple custom seekbar with hint, even an fresher can understand.

Any queries please post, Happy to help :) 

There is a sample application, please have a look at it. You will understand.
