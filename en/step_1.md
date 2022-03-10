Import Speaker from the picozero library then set the pins for multiple buzzers, use the following code: 

--- code ---
---
language: python
filename: 
line_numbers: false
line_number_start: 1
line_highlights: 
---
from picozero import Speaker

speaker_1 = Speaker(5)
speaker_2 = Speaker(10)
--- /code ---

**Tip**: You might want to use variable names that are specific to what the speaker should do. For example, `drum_beat`.
