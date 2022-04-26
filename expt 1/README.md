# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min.required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:
Registeration Number :
*/
```
### MainActivity.java
```
package com.example.helloworld;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Invoked",Toast.LENGTH_LONG);
        toast.show();
    }
}
```
### activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT:
![96e03d29-69ed-4762-b772-5cb8db426e1c](https://user-images.githubusercontent.com/75235159/165219068-5c7ce87d-6685-4991-94e6-f630e66740d8.jpg)
![78d174fe-ac98-4993-9dca-b82e14cb3ed2](https://user-images.githubusercontent.com/75235159/165219074-cd83cabb-9a94-4b0d-8089-fa9cc66458f0.jpg)
![c1a471d3-d9a1-4154-9061-ef60607a730c](https://user-images.githubusercontent.com/75235159/165219088-7ec50328-aceb-4a3f-9f53-cc191f1a590d.jpg)
![05f90615-f06a-46d6-99ce-1f78de0e8939](https://user-images.githubusercontent.com/75235159/165219112-f91ad336-cd45-402c-a08a-4d541b33b085.jpg)
![f49b4397-81d1-4fe1-871d-cffbd9e6449d](https://user-images.githubusercontent.com/75235159/165219194-478d694a-bbc1-47bd-a51d-73372d8ecfd6.jpg)
![44155d28-ce61-4da0-9d36-86aaccb39476](https://user-images.githubusercontent.com/75235159/165219209-004d3bff-3d29-44f0-ab62-61b7afd4da84.jpg)
![b1b486d1-83c1-49ae-91c1-c2ddfe05896a](https://user-images.githubusercontent.com/75235159/165219234-606f10d1-10e2-4252-b65e-426fc1ff78a2.jpg)

## RESULT:
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
