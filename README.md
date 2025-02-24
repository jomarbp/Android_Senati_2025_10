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
