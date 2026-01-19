<h2 class="c-project-heading--task">Trigger the animation</h2>
--- task ---
You can make the animation run, when the environment changes.
--- /task ---

<h2 class="c-project-heading--explainer">Call your own funtion</h2>

The `for` loop can sit inside a function. This can be **called** whenever the humidity changes.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 35
line_highlights: 
---
def walking():
    for i in range(5):
        sense.set_pixels(pet1)
        sleep(0.5)
        sense.set_pixels(pet2)
        sleep(0.5)

while True:
    hum = sense.get_humidity()
    if hum > 50:
        walking()
--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

Change the humidity using the slider.

![the humidity slider set to 45%](images/humidity.png)
</div>
