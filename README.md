<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <!-- Campo Nome -->
    <EditText
        android:id="@+id/editTextNome"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Nome completo"
        android:inputType="textPersonName"
        android:padding="15dp" />

    <!-- Campo Email -->
    <EditText
        android:id="@+id/editTextEmail"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Email"
        android:inputType="textEmailAddress"
        android:padding="15dp" />

    <!-- Campo Sexo (RadioGroup) -->
    <RadioGroup
        android:id="@+id/radioGroupSexo"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:padding="15dp">

        <RadioButton
            android:id="@+id/radioMasculino"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Masculino"
            android:padding="15dp" />

        <RadioButton
            android:id="@+id/radioFeminino"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:baselineAligned="false"
            android:text="Feminino"
            android:padding="16dp" />
    </RadioGroup>

    <!-- Campo Escolaridade (Dropdown) -->
    <Spinner
        android:id="@+id/spinnerEscolaridade"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="16dp" />

    <!-- Botão de Cadastro -->
    <Button
        android:id="@+id/buttonCadastrar"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Cadastrar"
        tools:ignore="HardcodedText" />

</LinearLayout>
