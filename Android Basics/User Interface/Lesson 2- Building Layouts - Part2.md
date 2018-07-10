# Lesson 2: Building Layouts - Part2
* **2.1 Quiz: ViewGroups**
    + **[Intro+Quiz](https://youtu.be/VyyRDCy5Dus)**
    + **Here are the words we introduced in this video**
        1.  ViewGroups
        2.  Root View
        3.  Parent
        4.  Child
        5.  Sibling<br />
       You can look up their definitions in the [Vocab Glossary](https://developers.google.com/android/for-all/vocab-words/?utm_source=udacity&utm_medium=course&utm_campaign=android_basics).
    + **[Solution](https://youtu.be/VCHdZU02oOI)**
    ____
* **2.2 Quiz: Types of ViewGroups**
     +  **[Video](https://www.youtube.com/watch?v=qKk4l7mBN0c)**
     +  **[Link to the code](https://gist.github.com/anonymous/cd7fda2fa5c4062acb92)**
     +  **Here are the words we introduced in this video**
      1.  LinearLayout : We can arrange the element horizontal or vertical. 
      2.  RelativeLayout : Position relative to parent or other children views. <br />
            You can look up their definitions in the [Vocab Glossary](https://developers.google.com/android/for-all/vocab-words/?utm_source=udacity&utm_medium=course&utm_campaign=android_basics).
  <img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b33e4e7_screen-shot-2018-06-27-at-12.26.16-pm/screen-shot-2018-06-27-at-12.26.16-pm.png" width="250px"/> <br />
     * **Write down 3 observations about the code linked above.**
        * Things to think about
            1. opening tag.
            2. new attribute: android:orientation.
            3. two TextViews.
            4. closing tag.
      * **[Solution](https://www.youtube.com/watch?v=3oaezVvplsk)**
___
* **2.3 Quiz: LinearLayout**
    + **[Video](https://youtu.be/-pNDpFnsE34)**
    + **[XML Visulaizer](https://labs.udacity.com/android-visualizer/#/android/linear-layout)**
    + **[Solution](https://youtu.be/MxoWZUJNCUQ)**
___
* **2.4 Quiz: Width & Height**
    + **[LinearLayout: Width & Height](https://youtu.be/EWWlS8QmKO8)**
      * We can use one of the 3 methods to percise the size of a view, width&height, wrap_content (take size of the element) & match_parent (take the size of the parent).
    + **[Link to the XML visualizer](https://labs.udacity.com/android-visualizer/#/android/match-parent)**
    + **Here are the words we introduced in this video**
      1.  match_parent. (Take parent size)
      2.  ViewGroup layout parameter.
            You can look up their definitions in the [Vocab Glossary.](https://developers.google.com/android/for-all/vocab-words/?utm_source=udacity&utm_medium=course&utm_campaign=android_basics)
    + **[Width&Height Solutuion](https://www.youtube.com/watch?v=NQeEhWiWAlE)**     
 ___
* **2.5 Quiz: Evenly Spacing Out Children Views**
    + **[Video -> What's Evenly spacing?](https://www.youtube.com/watch?v=--uAaHickMQ)**
    + **[Article:LinearLayout weight]**
    + You can experiment with the XML [here](https://labs.udacity.com/android-visualizer/#/android/equal-space-children)**
    + See Stack Overflow for more info on **[LinearLayout: equally spaced children](https://stackoverflow.com/questions/3470420/is-it-possible-to-evenly-distribute-buttons-across-the-width-of-an-android-linea)**
    + **[Quiz Solution](https://www.youtube.com/watch?v=WfJphhj61js)**
___
* **2.6 Quiz: Layout Weight**
    + **[Layout weight: video](https://youtu.be/XkHDQwXYWvU)**
    + to make an evenly space between children, we should use `android:layout_weight="1"` and `android:layout_height="0px"`
    + Link to the **[XML visualizer](https://labs.udacity.com/android-visualizer/#/android/linear-layout-weight)**
    + Here are the words we introduced in this video:
      1. layout_weight : A **View** is a rectangular area on the screen. A **LinearLayout** is a big view that can contain smaller Views, called its children. A horizontal LinearLayout arranges its children in a row, and a vertical LinearLayout arranges them in a column. <br />
                         Each child in a horizontal LinearLayout can request a certain minimal amount of width for itself. If the layout is wide enough, it will have width left over after satisfying these requests.<br />
                         The leftover width is then parcelled out among the children that claim shares of it. The number of shares claimed by each child is called the **layout weight** of that child.<br />
    + You can look up their definitions in the [Vocab Glossary](https://developers.google.com/android/for-all/vocab-words/).
      + Hint: At 6:14, Katherine mentions we can use TextView with icons as buttons. Here's an example of how to do so. Note this is beyond the scope of the lesson, so don't worry if you don't understand it yet.
    +**[Solution](https://www.youtube.com/watch?v=5aJ6zJEPBHk)**
