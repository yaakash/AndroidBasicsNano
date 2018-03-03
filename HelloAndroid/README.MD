### UI XML
#### can be found inside: https://github.com/yaakash/AndroidBasicsNano/edit/master/HelloAndroid/app/src/main/res/layout/activity_main.xml

### App UI:
![helloandroid first project ui](https://user-images.githubusercontent.com/7467539/36931185-ca52220a-1ed6-11e8-8f3d-992d3ce68dd1.png)

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
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
        android:scaleType="centerCrop" />

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
            android:text="@string/udacity_number"
            android:autoLink="phone"
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
            android:textColorLink="#ffffff"
            android:fontFamily="sans-serif-condensed"
            android:text="@string/udacity_website"
            android:autoLink="web"
            android:layout_margin="15dp"
            android:textAppearance="?android:textAppearanceLarge"
            />
        </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
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
            android:autoLink="map"
            android:text="@string/udacity_address"
            android:layout_margin="15dp"
            android:textAppearance="?android:textAppearanceLarge"
            />
    </LinearLayout>


</LinearLayout>

