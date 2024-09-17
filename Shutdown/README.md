# Shutdown.bat

## 🛑 Description:
This batch script allows you to shut down your system either immediately or after a specified time delay. It can be useful for automating shutdowns after a task completes or for scheduled power-offs.

## 🚀 Usage:
1. Double-click `Shutdown.bat` to run the script.
2. By default, it will prompt for immediate shutdown.
3. To add a time delay (e.g., 60 seconds), you can edit the script or run it like this:
   
   ```
   shutdown.exe -s -t 60 -c "Testing"
   ```
Replace 60 with the number of seconds you want to delay the shutdown.

## ⚠️ Warning:
This script will forcefully shut down your system. Make sure to save all your work before running it.

Example:
```
shutdown.bat /t 30   # Shuts down after 30 seconds
