
## SAutoBgButton for Android

A subclass of the Button widget that automatically darkens the button's background when pressed, and sets it to transparent when disabled. This is inspired by iOS' automatic handling of custom background images for buttons.


### Usage

1. Copy and paste the `net` folder into your Android project's `src` folder.
2. Replace your button declarations to use `net.shikii.widgets.SAutoBgButton` instead of just `Button`:

    From this:

        <Button
          android:layout_width="wrap_content" android:layout_height="wrap_content"
          android:background="@drawable/button_blue_bg"
          android:text="Button with background image" />

    To this:

        <net.shikii.widgets.SAutoBgButton
          android:layout_width="wrap_content" android:layout_height="wrap_content"
          android:background="@drawable/button_blue_bg"
          android:text="Button with background image" />

