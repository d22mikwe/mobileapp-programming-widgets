
# Rapport


Jag har ändrat layouten till horizontel genom att ändra en kodrad till horizontel i activity_main.xml
```
android:orientation="horizontal"
```
Jag har även lagt till 3 stycken knappar. Dessa knappar har olika färger och olika texter som attribut.
Jag sänkte margin och layout width så att knapparna inte skulle vara så stora och för
att dem skulle få plats på samma rad.

```
<Button
        android:id="@+id/button"
        android:layout_width="105dp"
        android:layout_height="wrap_content"
        android:layout_margin="15dp"
        android:background="#EF0E0E"
        android:text="I am Red" />

    <Button
        android:id="@+id/button2"
        android:layout_width="105dp"
        android:layout_height="wrap_content"
        android:layout_margin="15dp"
        android:background="#09187C"
        android:text="I am Blue" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="15dp"
        android:layout_weight="1"
        android:background="#118E30"
        android:text="I am Green" />
```


