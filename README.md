# Remainder-Application
pip insatll plyer
import time
from plyer import notification
if __name__ == "__main__":
    while True:
        notification.notify(
            title="please Drink Water Now!!",
            message="About 15.5 cups (3.7 liters) of fluids a day for About 11.5 cups (2.7 liters) of fluids a day for women.",
            timeout=10
        )
        time.sleep(60*60)
