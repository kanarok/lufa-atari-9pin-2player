# lufa-atari-9pin-2player
Arduino Leonardo with LUFA for 2 Players

Pinout
				(n/a)
Pin	Mouse/Trackball		Lightpen	Joystick	Paddle		Dir	Comment
1	V-Pulse			n/c		/Forward	Button 3	IN
2	H-Pulse			n/c		/Back		n/c		IN
3	VQ-Pulse		n/c		/Left		Button 1	IN
4	HQ-Pulse		n/c		/Right		Button 2	IN
5	Button 3 (M)		Penpress	n/c		PotX		BOTH
6	Button 1 (L)		/Beamtrigger	/Button 1	n/c		BOTH
7	+5V			+5V		+5V		+5V		OUT	50mA max
8	GND			GND		GND		GND		--
9	Button 2 (R)		Button 2	Button 2	PotY		BOTH

Pot: linear 470kOhm
Dir: relative to host

Host:		Device:
1 2 3 4 5	5 4 3 2 1
 6 7 8 9         9 8 7 6
