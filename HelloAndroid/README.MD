### UI XML
#### can be found inside: https://github.com/yaakash/AndroidBasicsNano/edit/master/HelloAndroid/app/src/main/res/layout/activity_main.xml

### App UI:
![helloandroid first project ui](https://user-images.githubusercontent.com/7467539/36889023-1a1e8116-1e1e-11e8-9b77-3b2b836e35a0.png)


<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="#fff"
    tools:context="w.yaakash.helloandroid.MainActivity">


    <ImageView
        android:layout_width="match_parent"
        android:layout_height="250dp"
        android:src="@drawable/udacity_logo"
        android:scaleType="centerCrop">

    <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="#1E88E5"
            android:orientation="horizontal">

            <ImageView
                android:layout_width="30dp"
                android:layout_height="30dp"
                android:layout_margin="15dp"
                android:src="@drawable/user" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textColor="#ffffff"
                android:fontFamily="sans-serif-condensed"
                android:text="@string/Udacity"
                android:layout_margin="15dp"
                android:textAppearance="?android:textAppearanceLarge"
                />
        </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#455A64"
        android:orientation="horizontal">

        <ImageView
            android:layout_width="30dp"
            android:layout_height="30dp"
            android:layout_margin="15dp"
            android:src="@drawable/smartphone" />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textColor="#fff"
            android:fontFamily="sans-serif-condensed"
            android:text="650-555-5555"
            android:layout_margin="15dp"
            android:textAppearance="?android:textAppearanceLarge"
            />
        </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#455A64"
        android:orientation="horizontal">

        <ImageView
            android:layout_width="30dp"
            android:layout_height="30dp"
            android:layout_margin="15dp"
            android:src="@drawable/nav" />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textColor="#fff"
            android:fontFamily="sans-serif-condensed"
            android:text="www.udacity.com"
            android:layout_margin="15dp"
            android:textAppearance="?android:textAppearanceLarge"
            />
        </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#455A64"
        android:orientation="horizontal">

        <ImageView
            android:layout_width="30dp"
            android:layout_height="30dp"
            android:layout_margin="15dp"
            android:src="@drawable/placeholder" />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textColor="#ffffff"
            android:fontFamily="sans-serif-condensed"
            android:text="2465 Latham St. Mountain View CA 94043"
            android:layout_margin="15dp"
            android:textAppearance="?android:textAppearanceLarge"
            />
    </LinearLayout>

</LinearLayout>
