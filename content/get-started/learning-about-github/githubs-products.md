<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:paddingLeft="16dp"
        android:paddingRight="16dp"/>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="75dp"
        android:autoSizeMaxTextSize="30dp"
        android:autoSizeMinTextSize="12dp"
        android:autoSizeTextType="uniform"
        android:fontFamily="sans-serif-black"
        android:gravity="center"
        android:text="Layout"/>

    <androidx.cardview.widget.CardView
        android:id="@+id/cardview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_gravity="center"
        android:layout_marginBottom="50dp"
        app:cardBackgroundColor="@color/blue2"
        app:cardCornerRadius="20dp"
        app:cardElevation="20dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        tools:ignore="MissingClass">

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="175dp"
            android:scaleType="centerCrop"
            android:src="@drawable/gambar" />

        <EditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="200dp"
            android:layout_marginRight="10dp"
            android:hint="NIM"/>
        <EditText
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="250dp"
            android:layout_marginRight="10dp"
            android:layout_weight="1"
            android:gravity="top"
            android:hint="NAMA" />
        <EditText
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="305dp"
            android:layout_marginRight="10dp"
            android:layout_weight="1"
            android:hint="e-mail" />

        <Button
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:layout_marginLeft="16dp"
            android:layout_marginTop="370dp"
            android:layout_marginRight="16dp"
            android:background="@color/blue"
            android:text="LOGIN" />

    </androidx.cardview.widget.CardView>

</RelativeLayout>
