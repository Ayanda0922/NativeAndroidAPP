# NativeAndroidAPP
rivate fun Nothing?.joinToString(s: String) {

}

class MainActivity2 : AppCompatActivity() {

fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main2)

     lateinit var editTextDay1: EditText
     lateinit var editTextDay2: EditText
     lateinit var editTextDay3: EditText
     lateinit var editTextDay4: EditText
     lateinit var editTextDay5: EditText
     lateinit var editTextDay6: EditText
     lateinit var editTextDay7: EditText
     lateinit var resultTextView: TextView

    editTextDay1 = findViewById(R.id.Day1)
    editTextDay2 = findViewById(R.id.Day2)
    editTextDay3 = findViewById(R.id.Day3)
    editTextDay4 = findViewById(R.id.Day4)
    editTextDay5 = findViewById(R.id.Day5)
    editTextDay6 = findViewById(R.id.Day6)
    editTextDay7 = findViewById(R.id.Day7)
    resultTextView = findViewById(R.id.TextViewResult)

    val buttonCalculateAverage: Button = findViewById(R.id.calculateAverageButton)
    val buttonReset: Button = findViewById(R.id.ResettButton)
    val buttonSummary: Button = findViewById(R.id.ButtonEnterTemps)


    fun calculateAverage() {
        val temperatures = listOf(
            editTextDay1.text.toString().toDoubleOrNull(),
            editTextDay2.text.toString().toDoubleOrNull(),
            editTextDay3.text.toString().toDoubleOrNull(),
            editTextDay4.text.toString().toDoubleOrNull(),
            editTextDay5.text.toString().toDoubleOrNull(),
            editTextDay6.text.toString().toDoubleOrNull(),
            editTextDay7.text.toString().toDoubleOrNull(),

                fun() {
                    editTextDay1.text.clear()
                    editTextDay2.text.clear()
                    editTextDay3.text.clear()
                    editTextDay4.text.clear()
                    editTextDay5.text.clear()
                    editTextDay6.text.clear()
                    editTextDay7.text.clear()
                    resultTextView.text = "Data reset."

                    editTextDay1.text.toString()
                    editTextDay2.text.toString()
                    editTextDay3.text.toString()
                    editTextDay4.text.toString()
                    editTextDay5.text.toString()
                    editTextDay6.text.toString()
                    editTextDay7.text.toString()

                    var temperatures = null
                    resultTextView.text = "Temperatures: ${temperatures.joinToString(", ")}"  }}}}
