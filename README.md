<div align="center">

# Majed Khaled Almutairi

### COMPUTER ENGINEERING STUDENT
### Software & Embedded Systems

Based in Kuwait · Open to relocating within KSA

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-121212?style=for-the-badge&logoColor=white)](https://portfolio-sigma-self-juhjmizuu9.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/majed-almutairi-7b30a5439/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:majedkhaled0606@gmail.com)

</div>

---

## About

Hello World. I'm Majed, a third-year Computer Engineering student at the American University of the Middle East (AUM) in Kuwait, expected to graduate in 2028.

I started making things through games in Unity and C#. Now I spend most of my time on embedded systems, with Arduino, sensors, soldering and 3D-printed parts holding it together. I like it because the code finally gets to do something physical.

> [!TIP]
> I'm looking for a research placement or internship from June to September 2027.
> The full write-ups for my projects are on my [portfolio](https://portfolio-sigma-self-juhjmizuu9.vercel.app), or you can [email me](mailto:majedkhaled0606@gmail.com).

## Right now: [racecar](https://github.com/majedkalmutairi/racecar)

A 1/10 scale RC car that learns to race by itself. You put it on a track it has never seen and it drives one slow lap to map it, then goes faster every lap after that. If I move the walls around, it notices and starts over from the slow lap. The only sensor is a 2D lidar, and all the compute sits on the car.

It starts in a custom 2D simulator built with Python and Pygame, so everything works there before it touches real hardware. That part is done. On 90 random tracks it finished every one without a crash, and its best lap came out 45 to 47% faster than its first race lap. Next is moving the same code onto a Traxxas Slash with a Jetson Orin Nano, an LD19 lidar and ROS 2.

<div align="center">
  <img src="https://raw.githubusercontent.com/majedkalmutairi/racecar/main/docs/sim_dashboard.gif" width="90%" alt="The racecar simulator dashboard: the car mapping a track with lidar and then racing the line it planned">
</div>

## Projects

### [Motorized Chainsaw Prop](https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/motorized-chainsaw-prop)

A wearable chainsaw prop with a motor-driven belt of teeth that really runs.

<p align="center">
  <a href="https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/motorized-chainsaw-prop"><img src="assets/chainsaw-prop.webp" width="80%" alt="The motorized chainsaw prop on a desk, with its belt of foam teeth around the bar"></a>
</p>

I modelled the pulleys around the motor's D-shaped shaft and printed the bore about 2% undersize so it pressed on and stayed. The belt took longer. Glued leather strips kept snagging and tearing at the joints, so I stitched them instead, then glued HD foam teeth on top. I left that belt running for an hour and came back to find it still spinning.

<sub>Blender · 3D printing · Arduino · soldering</sub>

<br/>

### [Dosey](https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/dosey)

A medication and supplement reminder that runs entirely on your iPhone.

<p align="center">
  <a href="https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/dosey"><img src="assets/dosey-today.webp" width="26%" alt="Dosey's Today screen"></a>&nbsp;&nbsp;
  <a href="https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/dosey"><img src="assets/dosey-search.webp" width="26%" alt="Searching for a supplement in Dosey"></a>&nbsp;&nbsp;
  <a href="https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/dosey"><img src="assets/dosey-history.webp" width="26%" alt="Dosey's History screen"></a>
</p>

I started it to help my family remember their medication when I'm not around. My part was the product design and testing, plus the decisions along the way. There's no account and no server, so nothing leaves the phone. It reminds you before, at and after each dose and warns you before you run out. Its colours also shift with the time of day. It's on TestFlight with a handful of people.

<sub>iOS · Expo · TestFlight</sub>

<br/>

### Smaller builds

[Arduino Parking Occupancy System](https://portfolio-sigma-self-juhjmizuu9.vercel.app/projects/parking-system) tells drivers whether there's a free spot before they enter the lot. Two ultrasonic sensors watch two spots, a screen at the entrance shows something like "1/2 slots available", and a buzzer goes off when the lot is full. The hard part was the distance threshold: too high and the sensor read the floor as a car, too low and it missed small sedans and coupes. The idea, wiring, code, build and report were all mine.<br/>
<sub>Arduino · C++ · ultrasonic sensors</sub>

Gym NFC check-in <sub>(in progress, private repo)</sub>. Right now everyone at my university's gym writes their name, ID and time on a paper sheet when they walk in, and I'm replacing that with a tap of your student ID. An ESP32 reads the card with an RC522 reader, shows your name and the time on a small OLED, and beeps, then a Flask and SQLite server logs the visit. The reader side works on the breadboard and the server is next. It only reads the card's public UID, and the logs delete themselves after 7 days.<br/>
<sub>ESP32 · C++ · PlatformIO · Python · Flask</sub>

## Tools

<img src="https://skillicons.dev/icons?i=arduino,cpp,c,python,linux,ros,blender,unity,cs,git,github&theme=dark" alt="Arduino, C++, C, Python, Linux, ROS, Blender, Unity, C#, Git, GitHub">

Also Pygame, breadboarding and sensors, soldering, 3D printing and FreeCAD.

## Outside of engineering

I play electric guitar, mostly making songs up on the spot. I design props in Blender or CAD and print them out, ideally ones that move or have lights and sounds built in. When I'm not coming up with new projects to steal my time, I'm in the gym.
