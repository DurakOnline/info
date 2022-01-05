# Info
I have installed the game on a Nox emulator and that's what I found in the data folder of the app.
![folders inside com.rstgames.durak](/images/image1.png)
Inside the shared_prefs here is what you can found
![files inside shared_prefs](/images/image2.png)
In FLURRY_SHARED_PREFERENCES you can find this:
```xml
<?xml version='1.0' encoding='utf-8' standalone='yes' ?>
<map>
    <long name="com.flurry.sdk.frame.counter" value="17" />
    <long name="com.flurry.sdk.last_streaming_session_id" value="1641397710987" />
    <int name="com.flurry.sdk.last_streaming_http_error_code" value="503" />
    <string name="com.flurry.sdk.last_streaming_http_report_identifier">7f3t5ebg-53d3-4ty9-878a-8d4aa9567814</string>
    <int name="com.flurry.sdk.prev_streaming_api_key" value="1790714537" />
    <string name="com.flurry.sdk.last_streaming_http_error_message">Can not parse http error message: NULL</string>
    <long name="com.flurry.sdk.initial_run_time" value="1640972805723" />
</map>
```
I've uploaded the SERVERS.xml file
And in the RSTGAMES.xml file you can find the following code
```xml
<?xml version='1.0' encoding='utf-8' standalone='yes' ?>
<map>
    <long name="coins" value="0" />
    <long name="score" value="474648" />
    <int name="userAchc" value="34" />
    <string name="avatar">http://static.rstgames.com/durak/avatar/058/339/58339319.jpg?1610826974348</string>
    <int name="numOfAchs" value="58" />
    <long name="points" value="155071" />
    <string name="rid">RjxuHYPP</string>
    <string name="dtp">2021-01-27T11:32:39</string>
    <string name="lastServName">uD</string>
    <string name="RSTGAMES-DURAK-TOKEN">$2a$06$Pl4ddcE7aM8nY2yL0Awdif1</string>
    <string name="name">😇😇😇</string>
    <int name="AuthDialogShowCount" value="3" />
    <long name="previous time" value="1639926712549" />
</map>
```
This is just to show what you can find inside de data folder, the value of each key has been modified, to try something you might need to install the game to get real data.
