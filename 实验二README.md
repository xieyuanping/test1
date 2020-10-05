1、线性布局

代码：

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical" android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/botton1"
            android:layout_width="90dp"
            android:layout_height="wrap_content"
            android:text="one_one" />

        <Button
            android:id="@+id/botton2"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="one_two" />

        <Button
            android:id="@+id/botton3"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="one_three" />

        <Button
            android:id="@+id/botton4"
            android:layout_width="95dp"
            android:layout_height="wrap_content"
            android:text="one_four" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/botton5"
            android:layout_width="90dp"
            android:layout_height="wrap_content"
            android:text="two_one" />

        <Button
            android:id="@+id/botton6"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="two_two" />

        <Button
            android:id="@+id/botton7"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="two_three" />

        <Button
            android:id="@+id/botton8"
            android:layout_width="95dp"
            android:layout_height="wrap_content"
            android:text="two_four" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/botton9"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="three_one" />

        <Button
            android:id="@+id/botton10"
            android:layout_width="90dp"
            android:layout_height="wrap_content"
            android:text="three_two" />

        <Button
            android:id="@+id/botton11"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="three_three" />

        <Button
            android:id="@+id/botton12"
            android:layout_width="95dp"
            android:layout_height="wrap_content"
            android:text="three_four" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/botton13"
            android:layout_width="90dp"
            android:layout_height="wrap_content"
            android:text="four_one" />

        <Button
            android:id="@+id/botton14"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="four_two" />

        <Button
            android:id="@+id/botton15"
            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="four_three" />

        <Button
            android:id="@+id/botton16"
            android:layout_width="95dp"
            android:layout_height="wrap_content"
            android:text="four_four" />
    </LinearLayout>
    </LinearLayout>
```

截图：<br>



2、ConstraintLayout

代码：

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <Button
        android:id="@+id/button1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#F44336"
        android:backgroundTint="#F44336"
        android:text="RED"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#FFEB3B"
        android:backgroundTint="#FFEB3B"
        android:text="YELLOW"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button4"
        android:layout_width="0dp"
        android:layout_height="67dp"
        android:layout_marginBottom="56dp"
        android:background="#E86B95"
        android:backgroundTint="#F66194"
        android:text="Button"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="320dp"
        android:layout_marginEnd="160dp"
        android:background="#3F51B5"
        android:backgroundTint="#3F51B5"
        android:text="BLUE"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="160dp"
        android:background="#FF9800"
        android:backgroundTint="#FF9800"
        android:text="ORANGER"
        app:layout_constraintStart_toEndOf="@+id/button1"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="32dp"
        android:layout_marginTop="320dp"
        android:background="#4CAF50"
        android:backgroundTint="#4CAF50"
        android:text="GREEN"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="320dp"
        android:layout_marginEnd="32dp"
        android:background="#673AB7"
        android:backgroundTint="#673AB7"
        android:text="INDIGO"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```

截图：<br>



3、表格布局

代码：

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android" android:layout_width="match_parent"
    android:layout_height="match_parent">
    <TableLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:shrinkColumns="0">

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#F3ECEC"
            android:gravity="left"

            android:text="open...                                                               ctrl+o">

        </Button>
        <Button
            android:layout_height="wrap_content"
            android:layout_width="wrap_content"
            android:text="save...                                                               ctrl+s"
            android:gravity="left"
            android:layout_marginTop="-11dp"
            >

        </Button>
        <Button
            android:layout_height="wrap_content"
            android:layout_width="wrap_content"
            android:text="save As...                                                       ctrl+shift+s"
            android:gravity="left"
            android:layout_marginTop="-11dp"
            >

        </Button>
        <View  android:layout_height="2px"
            android:layout_width="match_parent"
            android:background="#000000"
            android:layout_marginTop="-3dp"
            ></View>
        <Button
            android:layout_height="wrap_content"
            android:layout_width="wrap_content"
            android:text="Import..."
            android:gravity="left"
            android:layout_marginTop="-4dp"
            >
        </Button>
        <Button
            android:layout_height="wrap_content"
            android:layout_width="wrap_content"
            android:text="Export...                                                              ctrl+e"
            android:gravity="left"
            android:layout_marginTop="-11dp"
            >
        </Button>
        <View  android:layout_height="2px"
            android:layout_width="match_parent"
            android:background="#000000"
            android:layout_marginTop="-3dp"
            ></View>
        <Button
            android:layout_height="wrap_content"
            android:layout_width="wrap_content"
            android:text="quilt..."
            android:gravity="left"
            android:layout_marginTop="-4dp"
            >
        </Button>
    </TableLayout>

</androidx.constraintlayout.widget.ConstraintLayout>
```

截图：<br>
