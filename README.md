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
