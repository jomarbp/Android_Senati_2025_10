# botón actualizar

        <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <com.google.android.material.button.MaterialButton
            android:id="@+id/buttonSave"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Guardar"
            android:padding="12dp"
            android:layout_marginEnd="8dp"/>

        <com.google.android.material.button.MaterialButton
            android:id="@+id/buttonUpdate"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Actualizar"
            android:padding="12dp"
            android:enabled="false"
            style="@style/Widget.MaterialComponents.Button.OutlinedButton"/>
    </LinearLayout>

# user_item.xml


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:id="@+id/textViewName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:textSize="18sp"
                android:textStyle="bold"/>

            <TextView
                android:id="@+id/textViewEmail"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="4dp"/>

            <TextView
                android:id="@+id/textViewPhone"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="4dp"/>
        </LinearLayout>

        <ImageButton
            android:id="@+id/buttonDelete"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:src="@drawable/ic_delete"
            android:background="?attr/selectableItemBackgroundBorderless"
            android:padding="16dp"
            android:contentDescription="Eliminar usuario"/>

    </LinearLayout>

#icono eliminar

        <?xml version="1.0" encoding="utf-8"?>
        <vector xmlns:android="http://schemas.android.com/apk/res/android"
            android:width="24dp"
            android:height="24dp"
            android:viewportWidth="24"
            android:viewportHeight="24"
            android:tint="?attr/colorError">
            <path
                android:fillColor="@android:color/white"
                android:pathData="M6,19c0,1.1 0.9,2 2,2h8c1.1,0 2,-0.9 2,-2V7H6v12zM19,4h-3.5l-1,-1h-5l-1,1H5v2h14V4z"/>
        </vector>
