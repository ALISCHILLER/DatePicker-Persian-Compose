**Title:** DatePickersPersion: a Jetpack Compose library for date and time selection in Farsi language

**Summary:**

DatePickersPersion is a Jetpack Compose library that allows you to choose date and time in Farsi language. This library uses a simple and intuitive user interface that makes it easy.

#myGif
![]([https://github.com/Your_Repository_Name/Your_GIF_Name.gif](https://github.com/ALISCHILLER/DatePickersPersion/blob/main/media/Screen_Recording_20230919_162830_PersionCalendar.gif))

#myimage
![alt text]([http://url/to/img.png](https://github.com/ALISCHILLER/DatePickersPersion/blob/main/media/Screenshot_20230919_162724_PersionCalendar.jpg))
**Attributes:**

* Support for selecting the date and time in Farsi language
* Simple and intuitive user interface
* Ability to customize

**How to use:**

To use DatePickersPersion, you must first add it to your Jetpack Compose project. You can do this by adding the following substring to your build.gradle file:

```

All projects {
reservoirs
...
maven { url 'https://www.jitpack.io' }
}
}
```
```

Dependencies {
Implementation of 'com.github.ALISCHILLER:DatePickersPersion:Tag'
}
```

After installing the library, you can use it in your project. To do this, you need to add the `CalendarScreen` component to your Jetpack Compose file:

Kathleen
import com.github.ALISCHILLER.date_pickers_persian.DatePicker

@Composable
fun program () {
   calendar page (
   onDismiss = { hideDatePicker = true },
    onConfirm = { setDate = it }
     )
}
```


import com.github.ALISCHILLER.date_pickers_persian.DatePicker

@Composable
fun program () {
    calendar page (
     onDismiss = { hideDatePicker = true },
     onConfirm = { setDate = it }
   )
}
```

This code creates a simple `DatePicker` component and saves the selected date to a `date` variable.

**License:**

DatePickersPersion is released under the MIT license.

**connections:**

For more information, please visit the GitHub page: https://github.com/ALISCHILLER/DatePickersPersion.

**Version:** 0.0.1

**Date:** 2023-09-19

**Author:** Ali Soleimani

**Changes:**

* Version 0.0.1: Initial release

**Implementation:**


An onSelect event is called when the user selects a date or time. This event receives the date or selected value as a time.



**Development:**

The DatePickersPersion library is under development. In the future, new features support language development and support selection