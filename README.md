# pointhistory

Provides two rings `pointhistory-ring` and `pointhistory-auto-ring`
for remembering positions of point.
If a command moves point over a long distance. The previous point position
is stored in `pointhistory-auto-ring`.
You can return to these point positions by the command `pointhistory-auto-backward` (bound to <kbd>M-S-up</kbd>).
This is most useful if you accidently moved point and want to return to the previous position.

If you want to remember a point position for later use you can call `pointhistory-point2ring` (bound to <kbd>M-+</kbd>).
Press <kbd>M-up</kbd> to rotate through the remembered point positions.
