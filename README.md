NSBE
Google Quick Search Enabler

This is a simple shell script for Android that enables the Google Quick Search Box OneSearchAimActivity after a short delay

This is a simple shell script for Android that enables the **Google Quick Search Box OneSearchAimActivity** after a short delay.  

Script

```sh
#!/system/bin/sh

# Wait 20 seconds before executing
sleep 20

# Enable OneSearchAimActivity in Google Quick Search Box
pm enable com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.OneSearchAimActivity.

How It Works

1. The script waits for 20 seconds using sleep to allow the system to fully boot.

2. It then runs pm enable to enable the OneSearchAimActivity inside the Google Quick Search Box app.

3. This can be used in custom modules, Magisk scripts, or automation to restore functionality if it was disabled.
