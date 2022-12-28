Unscramble App
===================================

Store the data in a ViewModel

https://developer.android.com/courses/pathways/android-basics-kotlin-unit-3-pathway-3

Unscramble is  a single player game app that displays scrambled words. To play the game, player has
to make a word using all the letters from the displayed scrambled word.


Summary
--------------

- The Android app architecture guidelines recommend separating classes that have different responsibilities and driving the UI from a model.
- A UI controller is a UI-based class like Activity or Fragment. UI controllers should only contain logic that handles UI and operating system interactions; they shouldn't be the source of data to be displayed in the UI. Put that data and any related logic in a ViewModel.
- The ViewModel class stores and manages UI-related data. The ViewModel class allows data to survive configuration changes such as screen rotations.
- ViewModel is one of the recommended Android Architecture Components.

- LiveData holds data; LiveData is a wrapper that can be used with any data.
- LiveData is observable, which means that an observer is notified when the data held by the LiveData object changes.
- LiveData is lifecycle-aware. When you attach an observer to the LiveData, the observer is associated with a LifecycleOwner (usually an Activity or Fragment). The LiveData only updates observers that are in an active lifecycle state such as STARTED or RESUMED.
- Apps can listen to the LiveData changes from the layout using Data Binding and binding expressions.
- Binding expressions are written within the layout in the attribute properties (such as android:text) referencing the layout properties.


