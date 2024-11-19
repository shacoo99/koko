<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <EditText
        android:id="@+id/weightInput"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter your weight (kg)"
        android:inputType="numberDecimal"
        android:importantForAccessibility="yes" />

    <Button
        android:id="@+id/calculateButton"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="أحسب"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:textSize="26dp"
        android:backgroundTint="#52B5CA"
        android:layout_marginTop="16dp"
        android:importantForAccessibility="yes" />

    <TextView
        android:id="@+id/resultText"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textSize="16sp"
        android:paddingTop="16dp"
        android:text="Result will appear here"
        android:importantForAccessibility="yes" />

</LinearLayout>
