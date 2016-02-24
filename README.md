# birthday-card
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textAppearance="?android:attr/textAppearanceLarge"
        android:text="Happy Birthday !"
        android:id="@+id/textView"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:textColor="#8E24AA"
        android:textStyle="bold" />

    <LinearLayout
        android:orientation="vertical"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_below="@+id/textView"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginTop="78dp"
        android:weightSum="1"
        android:id="@+id/linearLayout">

        <ProgressBar
            style="?android:attr/progressBarStyleLarge"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/progressBar" />

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/imageView"
            android:layout_gravity="center_horizontal" />

        <ImageView
            android:id="@+id/photo_image_view"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:src="@drawable/androidbirthday" />

        <ProgressBar
            style="?android:attr/progressBarStyleLarge"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:id="@+id/progressBar2"
            android:indeterminate="false" />
    </LinearLayout>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textAppearance="?android:attr/textAppearanceMedium"
        android:text="wish u all the best"
        android:id="@+id/textView2"
        android:layout_gravity="center_horizontal"
        android:layout_alignTop="@+id/linearLayout"
        android:layout_alignLeft="@+id/textView"
        android:layout_alignStart="@+id/textView"
        android:textColor="#D32F2F"
        android:textStyle="bold" />
