import time
from datetime import datetime

while True:
    current_time = datetime.now().strftime("%A, %d %B %Y | %H:%M:%S")
    print(current_time)
    time.sleep(1)

