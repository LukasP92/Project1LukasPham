<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <RelativeLayout
        android:id="@+id/activity_main"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        tools:context="com.example.omig.project1.MainActivity">

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:scaleType="centerCrop"
            android:src="@drawable/bckgrnd"
            android:layout_alignParentTop="true"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true"
            android:id="@+id/imageView2" />

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="100dp"
            android:src="@drawable/bistro2"
            android:id="@+id/imageView"
            android:layout_marginBottom="65dp"/>

        <TextView
            android:id="@+id/bistro"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_centerHorizontal="true"
            android:layout_marginTop="25dp"
            android:text="Bistro Andel"
            android:textColor="#FFFFFF"
            android:textSize="50sp"
            android:textStyle="bold|italic" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@id/bistro"
            android:layout_centerHorizontal="true"
            android:text="http://www.andelcafe.cz/bistro/"
            android:textColor="#FFFFFF"
            android:textSize="15sp"
            android:textStyle="italic"
            android:id="@+id/textView3" />

        <TextView
            android:id="@+id/hour2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Sat - Sun: Closed"
            android:textColor="#FFFFFF"
            android:layout_marginRight="12dp"
            android:layout_marginEnd="12dp"
            android:layout_below="@+id/imageView"
            android:layout_alignParentRight="true"
            android:layout_alignParentEnd="true" />

        <TextView
            android:id="@+id/hour1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Mon-Fri: 09:00 - 16:30"
            android:textColor="#FFFFFF"
            android:layout_above="@+id/hour2"
            android:layout_alignRight="@+id/hour2"
            android:layout_alignEnd="@+id/hour2" />

        <TextView
            android:id="@+id/hour"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Hours of operation"
            android:textColor="#FFFFFF"
            android:textSize="17sp"
            android:textStyle="bold"
            android:layout_above="@+id/hour1"
            android:layout_alignRight="@+id/hour1"
            android:layout_alignEnd="@+id/hour1" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Plzen, Bezrucova 7"
            android:textColor="#FFFFFF"
            android:textSize="20sp"
            android:textStyle="italic"
            android:id="@+id/textView2"
            android:layout_above="@+id/hour"
            android:layout_alignRight="@+id/hour"
            android:layout_alignEnd="@+id/hour" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Tel: +420 777 022 235"
            android:textColor="#FFFFFF"
            android:textSize="13sp"
            android:textStyle="italic"
            android:id="@+id/textView"
            android:layout_alignTop="@+id/hour2"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true"
            android:layout_marginLeft="14dp"
            android:layout_marginStart="14dp" />


    </RelativeLayout>
</ScrollView>
