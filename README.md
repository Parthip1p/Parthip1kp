# import android.os.Bundle;
import android.widget.TextView;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Find the TextView element by its id
        TextView textView = findViewById(R.id.textView);

        // Get the string resource for "Hello, World!"
        String helloWorld = getString(R.string.hello_world);

        // Set the text of the TextView
        textView.setText(helloWorld);
    }
}
