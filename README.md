android-style
=============

To convert your inline style attribute to style tag 


<a href="http://htmlpreview.github.io/?https://github.com/palaniraja/android-style/blob/master/index.html">Demo</a>

From the following

<pre>
android:padding="30dp"
android:verticalSpacing="40dp"
android:horizontalSpacing="40dp"
android:numColumns="auto_fit"
android:columnWidth="80dp"     
</pre>
      
to

<pre>
<xmp>
<style name="REPLACETHIS">
<item name="android:padding">30dp</item>
<item name="android:verticalSpacing">40dp</item>
<item name="android:horizontalSpacing">40dp</item>
<item name="android:numColumns">auto_fit</item>
<item name="android:columnWidth">80dp</item>
</style>
</xmp>
</pre>
