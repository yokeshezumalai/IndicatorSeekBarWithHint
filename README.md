
<h1 align="center">IndicatorSeekBarWithHint</h1>
<p align="center">
 <a href="https://circleci.com/gh/yokeshezumalai/IndicatorSeekBarWithHint/tree/master"> <img src="https://circleci.com/gh/yokeshezumalai/IndicatorSeekBarWithHint/tree/master.svg?style=shield" /></a>
 <a href="https://jitpack.io/#yokeshezumalai/IndicatorSeekBarWithHint"><img src="https://jitpack.io/#yokeshezumalai/IndicatorSeekBarWithHint/month.svg"/></a>
 <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"/></a>
  <br /><br />
 </p>

A custom SeekBar on Android - Kotlin, will show hint view with progress above SeekBar when seeking.
A custom seek bar with floating textview

https://github.com/yokeshezumalai/IndicatorSeekBarWithHint

# Medium
https://medium.com/@yokeshezumalai/android-custom-seek-bar-with-floating-textview-1b904c8e7439

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

### License
```

MIT License

Copyright (c) 2019 Yokesh Ezumalai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
