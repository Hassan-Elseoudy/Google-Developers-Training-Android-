Lesson 1: Building Layouts - Part1
---
*  **1.1 [Welcome to the course](https://www.youtube.com/watch?v=LQpAmM4vznQ "Introduction")**
___
* **1.2 Introduction**<br />

In this course, you’ll learn how to use Android Studio, the tool that professional developers use to create apps.<br />
Be sure that your computer meets the system requirements for Android Studio.<br />
The course will take about 3 - 5 hours of dedicated work, but it can widely vary per student, so take your time to learn the concepts.<br />
One last note about prerequisites. If you have no prior programming experience, then this course is for you.<br />
We’ll assume that you already have basic computer skills and know how to use a smartphone.<br />
___
* **1.3 Preparing for the journey**<br />

	+ **Common obstacles**<br />
	When speaking with many students, we found common reasons why they were hesitant to start learning Android:
	1. Lack of confidence that they can be a developer
	2. Code seems intimidating
	3. Tools seem complex
	4. Too much jargon
	5. Concepts are too abstract
We take these obstacles seriously and came up with ways to try to help you overcome them. 
Our aim is to make the learning curve as comfortable as possible for you as a student, so your confidence grows with each new concept mastered.

	+ **Visuals**<br />
	For all the visual learners out there, we use lots of drawings, analogies, and props to explain technical concepts that otherwise could be confusing.

	+ **Vocab Glossary**<br />
	We also don’t want you to be overwhelmed by all the jargon that comes up, or to feel like you need to memorize it. As a result, we’ve created a custom vocabulary glossary to help you. 
	If you ever forget what a word means, you can check out the glossary for a beautiful image, description, and code sample.
	https://developers.google.com/android/for-all/vocab-words/?hl=en

	+ **Instructor Notes**<br />
	When navigating in the Udacity classroom, if you scroll vertically below a video, you’ll often find instructor notes. 
	In these notes, we’ve provided supplementary links to other resources that you can read to get more information about the concepts covered in the video.

	+ **Learning Something New**<br />
	If you’re motivated and willing to be persistent, we are fully confident in your ability to learn Android development. 
	We have thousands of students who have gone from no coding experience to building simple apps on their own. You can do this!<br />
	[Your Strength](https://youtu.be/DWl0Racf4Gg)
___
* **1.4 Quiz: Views** <br />

	The first thing in Android you need to learn is something called Views. <br />
	**[Views](https://youtu.be/ctvsMCVlENI)**<br />
	Camel case is a convention that is not limited to programming.<br />
	If you've ever used FedEx, listened to an iPod, created a PowerPoint, or eaten at McDonalds, you've encountered camel case!

	+	We used a lot of new words in this video!
		1. Layout
		2. User Interface
		3. TextView -> Any text you see on the screen.
		4. ImageView -> View that shows image.
		5. Button -> View that shows button.
		6. Camel case
	
<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b313e2f_screen-shot-2018-06-25-at-12.10.21-pm/screen-shot-2018-06-25-at-12.10.21-pm.png" width="200px"/> <br />
- Quiz: Views<br />
			A. ImageView<br />
			B. TextView<br />
			C. TextView<br />
			D. TextView<br />
			E. Button<br />

	+ [Solution video](https://www.youtube.com/watch?v=D-6V9CNb7Is)
___
* **1.5 Quiz: Picking Views For Youtube**
<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b317d49_screen-shot-2018-06-25-at-4.39.21-pm/screen-shot-2018-06-25-at-4.39.21-pm.png" width="200px"/>

+ Note <br />
	In the screenshot above, the YouTube icon is static and simply meant to reflect the App's branding.<br /> 
	There is no interactivity intended for it.<br />
	[Solution Video](https://www.youtube.com/watch?v=OgKWVAd2I4I)
___
* **1.6 Talk to your phone**<br />

	Here are the words we introduced in this [video](https://youtu.be/gONbjxZM-0s)
	1. Code
	2. XML -> Describe how your app gonna look
	3. Integrated development environment (IDE) : 
	This is the tool in which we will write our code.<br />
	Similar to how we can use GMail as the tool to write an email, to write code for Android, we will use an IDE an IDE called Android Studio.
___
* **1.7 Quiz: Using TextView** <br />

**[TextView Video](https://www.youtube.com/watch?v=qoyjqLcTbPM)<br />**
<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b32a257_screen-shot-2018-06-26-at-1.29.41-pm/screen-shot-2018-06-26-at-1.29.41-pm.png" width="300px"/><br />
<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b32a263_screen-shot-2018-06-26-at-1.29.57-pm/screen-shot-2018-06-26-at-1.29.57-pm.png" width="300px"/><br />

+ **Things to think about**
	1. Weird angle brackets
	2. Don't know what "android:text" means
	3. Says "Happy Birthday", which appears on phone
	4. Has height and width

[Solution video](https://www.youtube.com/watch?v=sNqq_1Yg_i0)
___
* **1.8 Quiz: XML Syntax** <br />
	
	+ Here are the words we introduced in this [video](https://youtu.be/s2VszKiPD0E)
	1. XML element
	2. Tag
	3. Self-closing tags -> <TextView "Blah Blah" />
	4. Attributes -> Determine behave of the View. between ""
	5. Syntax

	You can look up their definitions in the Vocab Glossary.<br />
	Believe it or not, professional developers don't memorize everything -- looking up information is a key part of the job!<br />
	+ **Correction:** We incorrectly listed one of the attributes to be android:layout_weight.<br />
	The correct attribute is android:layout_width.<br />
	+ **Solution**
	1. TextView
	2. android:text,android:textColor,android:background,android:layout_width,android:layout_height
	3. 6<br />
	+ **[XML](https://youtu.be/hqhfxmf_XtA)**
___
* **1.9 Chnage the TextView** <br />

	+ **[Change video](https://youtu.be/uuB1HApT9nk)**<br />
	+ Words we used in this video:
		1. Android Studio
		2. Device
		3. Density-Independent Pixels -> dp (size of view)
	+ **[XML Visualizer](https://labs.udacity.com/android-visualizer/#/android/text-view)**
	+ **[Android View Cheat Sheet](https://drive.google.com/file/d/0B5XIkMkayHgRMVljUVIyZzNmQUU/view)**
	+ **[Solution Video](https://www.youtube.com/watch?v=f3m2w4DxOtY)**
___
* **1.10 Quiz: Getting past errors** <br />

	**[Video](https://www.youtube.com/watch?v=chwcMqcoSS0)**<br />
	Note that Android uses the American-English spelling of the word "gray".

	+ **Debugging steps**
		1. Read the error message
		2. Compare to working code
		3. Undo
		4. Ask for help
	+ **[XML Visualizer](https://labs.udacity.com/android-visualizer/#/android/xml-syntax-errors)**<br />
	+	**[Sample code](https://gist.github.com/anonymous/8bb1c5d7e4d3e434fb10)** <br />
	+ **[How to take screenshot](https://developer.android.com/studio/debug/am-screenshot)**
+ Describe at least 2 problems you see.
	+	Things to think about
		1. TextView
		2. Closing tag
		3. 150dp
		4. "gray"

+ **[Solution Video](https://www.youtube.com/watch?v=Qb2JrOZpvOE)**
___
* **1.11 Quiz: Setting wrap content**<br />

	+	**[Wrap content](https://www.youtube.com/watch?v=6_BGuYSLDcI)**<br />
	Words we used in this video:
		* Hard coding
		* wrap_content
	+	**[XML Visualizer](https://labs.udacity.com/android-visualizer/#/android/wrap-content)**<br />
	+ **[Solution Video](https://www.youtube.com/watch?v=SwBg6HAZLbY)**
___
* **1.12 Quiz: TextView Text Size**

	+	**[Optional challenge: Learn about text appearance from this G+ #AndroidDev #Protip](https://plus.google.com/+AndroidDevelopers/posts/gQuBtnuk6iG)**<br />
	+	**[Material Design](https://material.io/design/typography/#typography-styles)**<br />
	+	**[XML Visualizer](https://labs.udacity.com/android-visualizer/#/android/text-size)**<br />
	For more Android development tips, search on social media for the hashtags #AndroidDev and #Protip
	+ New term we used in this video:
		*	Scale-Independent Pixels <br />
	+	**[Solution video](https://www.youtube.com/watch?v=BDI-CDUVQoA)**
___
* **1.13 Quiz: TextView Text Color** <br />

	+	**[Text color video](https://www.youtube.com/watch?v=tn6VeQtSJ6Q)**
	+	**[XML Visualize](https://labs.udacity.com/android-visualizer/#/android/text-color)**
	+	**[Material Design](http://www.google.com/design/spec/style/color.html#color-color-palette)**
	+	**[Solution video](https://youtu.be/DW-fBLQAUG4)**<br />
___
* **1.14 Quiz: Simple ImageView** <br />

	+ **[Video](https://www.youtube.com/watch?v=hNTo8luMTGM)**
	+ **[XML Visualizer](https://labs.udacity.com/android-visualizer/#/android/simple-imageview)**
	+ **[Solution](https://www.youtube.com/watch?v=otTh-IITKYk)**
___
* **1.15. Quiz: Documentation** <br />

+ **[Documentation video](https://www.youtube.com/watch?v=w5AP3gwH46I)**
+	**[References](https://developer.android.com/reference/packages)**
+	**[Link to the XML visualizer New term we used in this video](https://labs.udacity.com/android-visualizer/#/android/other-text-view-attributes)**
	If you're wondering which link to click, look for the first one that starts with [Android](developer.android.com.) 
	Any website that starts with that web address is part of the official Android developer website and documentation.
	+	[Solution video](https://www.youtube.com/watch?v=ZwxrOTduee0)
___
* **1.16 Chatting with Google's Kirill Grouchnikov** <br />

	+	**[Video](https://youtu.be/ZVC_ZmheVqw)**
	+	**[Material Design](https://material.io/design/introduction)**
