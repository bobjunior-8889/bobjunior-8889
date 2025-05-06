#import pywhatkit
import time
try:
    # Send message instantly
    pywhatkit.sendwhatmsg_instantly(
        phone_no="+1234567890",  
        message="Hello from Python!",
        wait_time=15
    )
    print("Message sent!")
except Exception as e:
    print(f"Error: [e]")
