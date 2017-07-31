## LottieDemo

This Demo contains a demo to use Lottie Library by Airbnb in an Android Project. An animation JSON file can be played using `LottieAnimationView`.

## How to use

The code consists of a simple Loading Animation using LottieAnimationView. User can play or pause the animation using the Button.

```
    <com.airbnb.lottie.LottieAnimationView
        android:id="@+id/animation_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        app:lottie_autoPlay="true"
        app:lottie_colorFilter="@color/colorAccent"
        app:lottie_fileName="loading.json"
        app:lottie_loop="true"/>
```

## Library used

Add Lottie dependency to your gradle file.

```
    dependencies {
        compile 'com.airbnb.android:lottie:2.0.0'
    }
```

## Reference

[Lottie Github Page](https://github.com/airbnb/lottie-android)