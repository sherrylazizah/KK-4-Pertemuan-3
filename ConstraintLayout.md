<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="@drawable/latar">

    <TextView
        android:id="@+id/textView2"
        android:layout_width="420dp"
        android:layout_height="50dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="1.0" />

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="131dp"
        android:layout_height="172dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.223"
        app:srcCompat="@drawable/icon" />

    <EditText
        android:id="@+id/editTextTextEmailAddress2"
        android:layout_width="253dp"
        android:layout_height="50dp"
        android:ems="10"
        android:hint="Masukan Nama"
        android:inputType="textEmailAddress"
        android:background="#8f8d86"
        android:textColor="#454441"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.475" />

    <EditText
        android:id="@+id/editTextTextPassword3"
        android:layout_width="248dp"
        android:layout_height="50dp"
        android:background="#9c9684"
        android:ems="10"
        android:hint="Masukan Sandi"
        android:inputType="textPassword"
        android:textColor="#454441"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.581" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="148dp"
        android:text="LOGIN"
        android:textStyle="bold"
        app:backgroundTint="#5c5c5b"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextTextPassword3"
        app:layout_constraintVertical_bias="0.943" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="153dp"
        android:layout_height="50dp"
        android:gravity="center"
        android:text="Verifikasi"
        android:background="#7d9668"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextTextPassword3"
        app:layout_constraintVertical_bias="0.103" />

</androidx.constraintlayout.widget.ConstraintLayout>
