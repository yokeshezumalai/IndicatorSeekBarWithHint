# IndicatorSeekBarWithHint
A custom SeekBar on Android, will show hint view with progress above SeekBar when seeking.

https://github.com/Yokeshthebouncer/IndicatorSeekBarWithHint

# Implementation

implementation 'com.github.Yokeshthebouncer:IndicatorSeekBarWithHint:1.0.0'

<com.yokesh.seekbarwithhint.SeekBar
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
       
       
User can customise the min and max value and they can also customise the progress text color and progress drawable. 

A simple custom seekbar with hint, even an fresher can understand.

Any queries plesee post, Happy to help :) 
