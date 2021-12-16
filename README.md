# -online-quiz-app
<resources xmlns:tools="http://schemas.android.com/tools">
<!-- Base application theme. -->
<style name="Theme.BasicMathApp" parent="Theme.MaterialComponents.DayNight.NoActionBar">
<!-- Primary brand color. -->
<item name="colorPrimary">@color/purple_500</item>
<item name="colorPrimaryVariant">@color/purple_700</item>
<item name="colorOnPrimary">@color/white</item>
<!-- Secondary brand color. -->
<item name="colorSecondary">@color/teal_200</item>
<item name="colorSecondaryVariant">@color/teal_700</item>
<item name="colorOnSecondary">@color/black</item>
<!-- Status bar color. -->
<item name="android:statusBarColor" tools:targetApi="l">?attr/colorPrimaryVariant</item>
<!-- Customize your theme here. -->
</style>
</resources>


<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"


xmlns:app="http://schemas.android.com/apk/res-auto"android:layout_width="match_parent" android:layout_height="wrap_content" android:layout_marginLeft="22dp" android:layout_marginRight="22dp" android:background="@drawable/bg" android:orientation="vertical">

<ImageView
android:id="@+id/imageView5" android:layout_width="100dp" android:layout_height="100dp" android:layout_marginTop="16dp" android:src="@drawable/correct_img" app:layout_constraintEnd_toEndOf="parent" app:layout_constraintStart_toStartOf="parent" app:layout_constraintTop_toTopOf="parent" app:srcCompat="@drawable/correct_img" />

<TextView
android:id="@+id/tvDialog_score" android:layout_width="match_parent" android:layout_height="wrap_content" android:layout_marginTop="50dp" android:layout_marginBottom="50dp" android:gravity="center" android:text="Score: 0" android:textAlignment="center" android:textColor="@android:color/black" android:textSize="20sp" android:textStyle="bold"
app:layout_constraintBottom_toTopOf="@+id/correct_ok" app:layout_constraintEnd_toEndOf="parent" app:layout_constraintStart_toStartOf="parent" app:layout_constraintTop_toBottomOf="@+id/imageView5" />

<Button
android:id="@+id/correct_ok" android:layout_width="wrap_content" android:layout_height="wrap_content" android:layout_gravity="center" android:layout_marginBottom="32dp" android:background="@drawable/button_bg" android:text="Ok" android:textColor="@android:color/white" android:textSize="20sp"  android:textStyle="bold" app:layout_constraintBottom_toBottomOf="parent" app:layout_constraintEnd_toEndOf="parent" app:layout_constraintStart_toStartOf="parent"/>
</androidx.constraintlayout.widget.ConstraintLayout>


