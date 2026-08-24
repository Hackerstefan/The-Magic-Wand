# The-Magic-Wand
I made a remote that can control 𝗲𝘃𝗲𝗿𝘆𝘁𝗵𝗶𝗻𝗴 !

I am bulding a remote straight out of Harry Potter. It can control nearly 𝗲𝘃𝗲𝗿𝘆𝘁𝗵𝗶𝗻𝗴. 
From tv's and air conditioning, to smart plugs, lights, computers (via wake_one_lan) and more. 
It has on off buttons, a screen to see what you are controlling, one knob to change volume or light intensity, 1 button to change the device and 2 configurable buttons to whatever you want.
It runs ESPHome and with open-source Home Assistant you can add devices of your choosing.

1. First i searched for the components neeeded. I settled with:
- esp32-s3 zero
- oled 1.3 screen
- 3.7V battery 
- ir sensor ky-005
- ec11 knob
- charging module tp4056
- 5 buttons

Here is link to the Wokwi Design
https://wokwi.com/projects/410433244849526785

2. I prepared my schematic inside wokwi , but since it doesnt have the esp32-s3 zero i used the one from xiao (xiao-esp32-c3)
<h4>Designing Schematic</h4>
<a href="https://lapse.hackclub.com/timelapse/1qr9pF6XYkWM">
  <img src="https://img.shields.io/badge/▶_Watch_Timelapse-Designing_Schematic-ec3750?style=for-the-badge" alt="Designing Schematic">
</a>

https://github.com/user-attachments/assets/9900c0e7-90d5-4775-a31c-7cc3af49b593


3. Next i tested it

<h4>Testing Schematic</h4>
<a href="https:/
/lapse.hackclub.com/timelapse/kPnVVtXqYQ04">
  <img src="https://img.shields.io/badge/▶_Watch_Timelapse-Testing_Schematic-ec3750?style=for-the-badge" alt="Testing Schematic">
</a>

https://github.com/user-attachments/assets/3cf6a18c-cae7-4f43-8a4b-7c22fe5a22d8

4. Here is how it looks in the end.

<img width="288" height="323" alt="Screenshot From 2026-08-24 14-14-35" src="https://github.com/user-attachments/assets/d9dd6cea-7e5b-4901-81e1-15598394ab4e" />

5. Then i put all components on paper and drew the design.
<img width="347" height="500" alt="magicwand" src="https://github.com/user-attachments/assets/118badd7-f647-4507-b95b-2edeef633ac6" />
