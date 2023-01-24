This payload is designed to execute a series of commands on a Windows machine when a rubber ducky is plugged in.

Usage

    Plug in the FlipperZero to the target machine.
    Run in BasdUSB mode
    The payload will execute in the background, opening a hidden instance of Google Chrome and navigating to a specified URL.
    The payload will then open a Command Prompt window and execute a series of commands to clear the Chrome cache.
    Once the cache is cleared, the Command Prompt window will close and the payload will be complete.

Payload Details

    The payload starts by delaying for 1000 milliseconds (1 second).
    It then opens the Run dialog by pressing the Windows + r keys.
    Another delay of 100 milliseconds is added before executing the command to open chrome in hidden window
    The payload then opens a hidden instance of Google Chrome and navigates to the specified URL.
    After a delay of 5000 milliseconds (5 seconds), the Run dialog is opened again.
    The Command Prompt is then opened and the payload changes the current directory to the Chrome cache location.
    The payload then clears the Chrome cache by deleting all files in the cache directory.
    Finally, the Command Prompt is closed and the payload is complete.

Customization

    The URL that Google Chrome navigates to can be customized by changing the string "https://www.example.com/file.exe" to the desired URL.
    The delay times can also be adjusted if necessary.

Disclaimer

Please use this payload only for lawful and ethical purposes, and always have the user's consent before deploying it. Misuse of this payload may lead to legal consequences.