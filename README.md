- 👋 Hi, I’m @long890
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
long890/long890 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
provide me with the detailed full version of assembly code: you are to write an assembly language program that implements a real-time binary clock. Display
a binary version of time on the 10 LEDs on the DE1-SoC board. We want to display both seconds and hundredths
of a second. The seconds should be displayed on the high-order 3 bits of the red LEDS (i.e. LEDR9:7) and the
hundredths of seconds should be displayed on the low-order 7 bits (i.e. LEDR6:0). Your code should keep the
seconds and hundredth seconds counting separately, which means you’ll need to write think about how to code so
that they work correctly together.
Measure time intervals of 0.01 seconds in your program by using polled I/O with the Timer. You should be able
to stop/run the clock by pressing any pushbutton KEY. When the clock reaches 810 seconds 9910 hundreths, it
should wrap around to 000:0000000.
