# Display Webpage demo (with WebView)

This assignment illustrates how to display a webpage from an Android application.

## Problem:

Implement an Android application that displays DLSU webpage on launch.


## Basic WebView usage in MainActivity.java:

```Java
   public void displayWebpage(){
        WebView wv = (WebView) findViewById(R.id.webviewdlsu);
        wv.loadUrl("http://www.dlsu.edu.ph");
    }
```

## Keypoints:

On layout xml:

```xml
 <WebView  xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/webviewdlsu"
    android:layout_width="match_parent"
    android:layout_height="match_parent" />
```


## Screenshots:

![alt tag](https://github.com/wynsean/DisplayWebpage/blob/master/Screenshot1.png)

![alt tag](https://github.com/wynsean/DisplayWebpage/blob/master/Screenshot2.png)



