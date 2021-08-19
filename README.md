# water-drinking-reminder
give you reminder for drinking water in every 60 minute.


import time
from plyer import notification

if __name__ == "__main__":
    while True:
        notification.notify(
        title = "please drink water",
        message = "good for health and skin",
        app_icon = "C:/Users/user pc/Downloads/icon.ico.ico",
        timeout=10
    )
    time.sleep(60*60)
