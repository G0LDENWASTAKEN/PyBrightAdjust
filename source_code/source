from datetime import datetime
import screen_brightness_control as sbc


start_time = "20:00:00"
end_time = "23:59:59"

now = datetime.now()

current_time = now.strftime("%H:%M:%S")

if current_time >= start_time:
    sbc.set_brightness(0)

else:
    sbc.set_brightness(100)

    
