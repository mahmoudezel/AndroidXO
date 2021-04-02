# AndroidXO
#### Android XO game

XML Code
-----------------------------------------------------------------------------------------------------------------------------------

<h4>
    
```

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#FFFFFF"
    android:orientation="vertical"
    tools:context="com.example.ezel.xo.MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_marginBottom="2dp"
        android:layout_weight="1">

        <TextView
            android:id="@+id/x_player"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="#000000"
            android:gravity="center"
            android:text="X Player : 0"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />

        <TextView
            android:id="@+id/o_player"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="#FFFFFF"
            android:gravity="center"
            android:text="O Player : 0"
            android:textColor="#000000"
            android:textSize="24sp" />
    </LinearLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="10">

        <GridLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_centerHorizontal="true"
            android:layout_centerVertical="true"
            android:orientation="vertical"
            android:rowCount="3">

            <Button
                android:id="@+id/button1"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginLeft="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button1"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button4"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginLeft="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button4"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button7"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginLeft="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button7"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button2"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button2"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button5"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button5"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button8"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button8"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button3"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button3"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button6"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button6"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />

            <Button
                android:id="@+id/button9"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginBottom="2dp"
                android:layout_marginRight="2dp"
                android:layout_rowWeight="1"
                android:background="#000000"
                android:fontFamily="sans-serif"
                android:onClick="button9"
                android:textColor="#FFFFFF"
                android:textSize="70sp"
                android:textStyle="bold" />
        </GridLayout>
    </RelativeLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">

        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="#FFFFFF"
            android:onClick="newGame"
            android:text="New Game"
            android:textColor="#000000"
            android:textSize="24sp" />

        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="#000000"
            android:onClick="newRound"
            android:text="New Round"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />
    </LinearLayout>
</LinearLayout>

```

<h4>
    
Java Code
-----------------------------------------------------------------------------------------------------------------------------------

<h4>
    
```

package com.example.ezel.xo;

import android.content.res.Configuration;
import android.graphics.Color;
import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;

import java.util.Locale;

public class MainActivity extends AppCompatActivity {
    private int X = 0, O = 0;
    private String XO = "";
    private boolean isFinished = false;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        String languageToLoad = "en_US";
        Locale locale = new Locale(languageToLoad);
        Locale.setDefault(locale);
        Configuration config = new Configuration();
        config.locale = locale;
        getBaseContext().getResources().updateConfiguration(config, getBaseContext().getResources().getDisplayMetrics());
        this.setContentView(R.layout.activity_main);
    }

    private void XorO() {
        TextView xPlayerScore = (TextView) findViewById(R.id.x_player);
        TextView oPlayerScore = (TextView) findViewById(R.id.o_player);
        Button button1 = (Button) findViewById(R.id.button1);
        Button button2 = (Button) findViewById(R.id.button2);
        Button button3 = (Button) findViewById(R.id.button3);
        Button button4 = (Button) findViewById(R.id.button4);
        Button button5 = (Button) findViewById(R.id.button5);
        Button button6 = (Button) findViewById(R.id.button6);
        Button button7 = (Button) findViewById(R.id.button7);
        Button button8 = (Button) findViewById(R.id.button8);
        Button button9 = (Button) findViewById(R.id.button9);

        if ((("X").equals(button1.getText()) && ("X").equals(button2.getText()) && ("X").equals(button3.getText()) ||
                ("X").equals(button1.getText()) && ("X").equals(button4.getText()) && ("X").equals(button7.getText()) ||
                ("X").equals(button4.getText()) && ("X").equals(button5.getText()) && ("X").equals(button6.getText()) ||
                ("X").equals(button7.getText()) && ("X").equals(button8.getText()) && ("X").equals(button9.getText()) ||
                ("X").equals(button3.getText()) && ("X").equals(button6.getText()) && ("X").equals(button9.getText()) ||
                ("X").equals(button1.getText()) && ("X").equals(button5.getText()) && ("X").equals(button9.getText()) ||
                ("X").equals(button3.getText()) && ("X").equals(button5.getText()) && ("X").equals(button7.getText()) ||
                ("X").equals(button2.getText()) && ("X").equals(button5.getText()) && ("X").equals(button8.getText())) && !isFinished) {
            X++;
            xPlayerScore.setText("X Player : " + X);
            isFinished = true;
            if (("X").equals(button1.getText()) && ("X").equals(button2.getText()) && ("X").equals(button3.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button2.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button2.setTextColor(Color.parseColor("#000000"));
                button3.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button1.getText()) && ("X").equals(button4.getText()) && ("X").equals(button7.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button4.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button4.setTextColor(Color.parseColor("#000000"));
                button7.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button4.getText()) && ("X").equals(button5.getText()) && ("X").equals(button6.getText())) {
                button4.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button6.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button4.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button6.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button7.getText()) && ("X").equals(button8.getText()) && ("X").equals(button9.getText())) {
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button8.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setTextColor(Color.parseColor("#000000"));
                button8.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button3.getText()) && ("X").equals(button6.getText()) && ("X").equals(button9.getText())) {
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button6.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setTextColor(Color.parseColor("#000000"));
                button6.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button1.getText()) && ("X").equals(button5.getText()) && ("X").equals(button9.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button3.getText()) && ("X").equals(button5.getText()) && ("X").equals(button7.getText())) {
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button7.setTextColor(Color.parseColor("#000000"));
            } else if (("X").equals(button2.getText()) && ("X").equals(button5.getText()) && ("X").equals(button8.getText())) {
                button2.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button8.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button2.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button8.setTextColor(Color.parseColor("#000000"));
            }
        } else if ((("O").equals(button1.getText()) && ("O").equals(button2.getText()) && ("O").equals(button3.getText()) ||
                ("O").equals(button1.getText()) && ("O").equals(button4.getText()) && ("O").equals(button7.getText()) ||
                ("O").equals(button4.getText()) && ("O").equals(button5.getText()) && ("O").equals(button6.getText()) ||
                ("O").equals(button7.getText()) && ("O").equals(button8.getText()) && ("O").equals(button9.getText()) ||
                ("O").equals(button3.getText()) && ("O").equals(button6.getText()) && ("O").equals(button9.getText()) ||
                ("O").equals(button1.getText()) && ("O").equals(button5.getText()) && ("O").equals(button9.getText()) ||
                ("O").equals(button3.getText()) && ("O").equals(button5.getText()) && ("O").equals(button7.getText()) ||
                ("O").equals(button2.getText()) && ("O").equals(button5.getText()) && ("O").equals(button8.getText())) && !isFinished) {
            O++;
            oPlayerScore.setText("O Player : " + O);
            isFinished = true;
            if (("O").equals(button1.getText()) && ("O").equals(button2.getText()) && ("O").equals(button3.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button2.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button2.setTextColor(Color.parseColor("#000000"));
                button3.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button1.getText()) && ("O").equals(button4.getText()) && ("O").equals(button7.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button4.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button4.setTextColor(Color.parseColor("#000000"));
                button7.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button4.getText()) && ("O").equals(button5.getText()) && ("O").equals(button6.getText())) {
                button4.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button6.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button4.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button6.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button7.getText()) && ("O").equals(button8.getText()) && ("O").equals(button9.getText())) {
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button8.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setTextColor(Color.parseColor("#000000"));
                button8.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button3.getText()) && ("O").equals(button6.getText()) && ("O").equals(button9.getText())) {
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button6.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setTextColor(Color.parseColor("#000000"));
                button6.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button1.getText()) && ("O").equals(button5.getText()) && ("O").equals(button9.getText())) {
                button1.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button9.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button1.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button9.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button3.getText()) && ("O").equals(button5.getText()) && ("O").equals(button7.getText())) {
                button3.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button7.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button3.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button7.setTextColor(Color.parseColor("#000000"));
            } else if (("O").equals(button2.getText()) && ("O").equals(button5.getText()) && ("O").equals(button8.getText())) {
                button2.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button5.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button8.setBackgroundColor(Color.parseColor("#FFFFFF"));
                button2.setTextColor(Color.parseColor("#000000"));
                button5.setTextColor(Color.parseColor("#000000"));
                button8.setTextColor(Color.parseColor("#000000"));
            }
        } else if (!"".equals(button1.getText()) && !"".equals(button2.getText()) &&
                !"".equals(button3.getText()) && !"".equals(button4.getText())
                && !"".equals(button5.getText()) && !"".equals(button6.getText()) &&
                !"".equals(button7.getText()) && !"".equals(button8.getText()) &&
                !"".equals(button9.getText())) {
            return;
        }
    }

    public void newGame(View view) {
        TextView xPlayerScore = (TextView) findViewById(R.id.x_player);
        TextView oPlayerScore = (TextView) findViewById(R.id.o_player);
        Button button1 = (Button) findViewById(R.id.button1);
        Button button2 = (Button) findViewById(R.id.button2);
        Button button3 = (Button) findViewById(R.id.button3);
        Button button4 = (Button) findViewById(R.id.button4);
        Button button5 = (Button) findViewById(R.id.button5);
        Button button6 = (Button) findViewById(R.id.button6);
        Button button7 = (Button) findViewById(R.id.button7);
        Button button8 = (Button) findViewById(R.id.button8);
        Button button9 = (Button) findViewById(R.id.button9);
        X = 0;
        O = 0;
        XO = "";
        isFinished = false;
        xPlayerScore.setText("X Player : " + X);
        oPlayerScore.setText("O Player : " + O);
        button1.setText("");
        button2.setText("");
        button3.setText("");
        button4.setText("");
        button5.setText("");
        button6.setText("");
        button7.setText("");
        button8.setText("");
        button9.setText("");
        button1.setBackgroundColor(Color.parseColor("#000000"));
        button2.setBackgroundColor(Color.parseColor("#000000"));
        button3.setBackgroundColor(Color.parseColor("#000000"));
        button4.setBackgroundColor(Color.parseColor("#000000"));
        button5.setBackgroundColor(Color.parseColor("#000000"));
        button6.setBackgroundColor(Color.parseColor("#000000"));
        button7.setBackgroundColor(Color.parseColor("#000000"));
        button8.setBackgroundColor(Color.parseColor("#000000"));
        button9.setBackgroundColor(Color.parseColor("#000000"));
        button1.setTextColor(Color.parseColor("#FFFFFF"));
        button2.setTextColor(Color.parseColor("#FFFFFF"));
        button3.setTextColor(Color.parseColor("#FFFFFF"));
        button4.setTextColor(Color.parseColor("#FFFFFF"));
        button5.setTextColor(Color.parseColor("#FFFFFF"));
        button6.setTextColor(Color.parseColor("#FFFFFF"));
        button7.setTextColor(Color.parseColor("#FFFFFF"));
        button8.setTextColor(Color.parseColor("#FFFFFF"));
        button9.setTextColor(Color.parseColor("#FFFFFF"));
    }

    public void newRound(View view) {
        Button button1 = (Button) findViewById(R.id.button1);
        Button button2 = (Button) findViewById(R.id.button2);
        Button button3 = (Button) findViewById(R.id.button3);
        Button button4 = (Button) findViewById(R.id.button4);
        Button button5 = (Button) findViewById(R.id.button5);
        Button button6 = (Button) findViewById(R.id.button6);
        Button button7 = (Button) findViewById(R.id.button7);
        Button button8 = (Button) findViewById(R.id.button8);
        Button button9 = (Button) findViewById(R.id.button9);
        XO = "";
        isFinished = false;
        button1.setText("");
        button2.setText("");
        button3.setText("");
        button4.setText("");
        button5.setText("");
        button6.setText("");
        button7.setText("");
        button8.setText("");
        button9.setText("");
        button1.setBackgroundColor(Color.parseColor("#000000"));
        button2.setBackgroundColor(Color.parseColor("#000000"));
        button3.setBackgroundColor(Color.parseColor("#000000"));
        button4.setBackgroundColor(Color.parseColor("#000000"));
        button5.setBackgroundColor(Color.parseColor("#000000"));
        button6.setBackgroundColor(Color.parseColor("#000000"));
        button7.setBackgroundColor(Color.parseColor("#000000"));
        button8.setBackgroundColor(Color.parseColor("#000000"));
        button9.setBackgroundColor(Color.parseColor("#000000"));
        button1.setTextColor(Color.parseColor("#FFFFFF"));
        button2.setTextColor(Color.parseColor("#FFFFFF"));
        button3.setTextColor(Color.parseColor("#FFFFFF"));
        button4.setTextColor(Color.parseColor("#FFFFFF"));
        button5.setTextColor(Color.parseColor("#FFFFFF"));
        button6.setTextColor(Color.parseColor("#FFFFFF"));
        button7.setTextColor(Color.parseColor("#FFFFFF"));
        button8.setTextColor(Color.parseColor("#FFFFFF"));
        button9.setTextColor(Color.parseColor("#FFFFFF"));
    }

    public void button1(View view) {
        Button button = (Button) findViewById(R.id.button1);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button2(View view) {
        Button button = (Button) findViewById(R.id.button2);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button3(View view) {
        Button button = (Button) findViewById(R.id.button3);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button4(View view) {
        Button button = (Button) findViewById(R.id.button4);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button5(View view) {
        Button button = (Button) findViewById(R.id.button5);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button6(View view) {
        Button button = (Button) findViewById(R.id.button6);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button7(View view) {
        Button button = (Button) findViewById(R.id.button7);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button8(View view) {
        Button button = (Button) findViewById(R.id.button8);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }

    public void button9(View view) {
        Button button = (Button) findViewById(R.id.button9);
        if (XO.equals("") && !isFinished) {
            button.setText("X");
            XO = "X";
        } else if (button.getText().equals("") && !isFinished) {
            if ((XO).equals("X")) {
                button.setText("O");
                XO = "O";
                XorO();
            } else if ((XO).equals("O")) {
                button.setText("X");
                XO = "X";
                XorO();
            }
        }
    }
}
    
```

<h4>
