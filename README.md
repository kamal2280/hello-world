# hello-world
just another repository
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        android:src="@drawable/androidparty" />

    <TextView
        android:text="Happy Birthday hamdy"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="34sp"
        android:fontFamily="sans-serif_light"
        android:textColor="@android:color/white"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentRight="true"
        android:layout_alignParentBottom="true"
        android:textSize="34sp"
        android:fontFamily="sans-serif_light"
        android:textColor="@android:color/white"
        android:text="From, Kamal" />

</RelativeLayout>
