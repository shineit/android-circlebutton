android-circlebutton
====================

Circle button widget for Android

![Button Example](example/example.gif)

[Download an example apk](example/example.apk)

Gradle dependency  ```build.gradle```

```
repositories {
    mavenCentral()
    mavenLocal()
}

...

dependencies {
    compile 'com.github.markushi:circlebutton:1.1'
}
```

Example Usage:
```
<FrameLayout
	xmlns:android="http://schemas.android.com/apk/res/android"
	xmlns:app="http://schemas.android.com/apk/res-auto"
	android:layout_width="match_parent"
	android:layout_height="match_parent" >

	<at.markushi.ui.CircleButton
		android:layout_width="64dip"
		android:layout_height="64dip"
		android:src="@drawable/ic_action_tick"
		app:cb_color="#99CC00"
		app:cb_pressedRingWidth="8dip" />

</FrameLayout>
```
