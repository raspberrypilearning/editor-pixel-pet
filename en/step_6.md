<h2 class="c-project-heading--task">Change the pet</h2>
--- task ---
Create and test a second version of your pet.
--- /task ---

<h2 class="c-project-heading--explainer">Write another list</h2>

Create a second list, with the changed version of your pet.

Test this out by changing which version is displayed on the LED display

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 24
line_highlights: 
---
pet2 = [
    e, e, e, e, e, e, e, e,
    p, e, e, e, e, e, e, e,
    e, p, e, e, p, e, p, e,
    e, p, g, g, p, w, w, e,
    e, g, g, g, w, y, w, y,
    e, g, g, g, g, w, w, e,
    e, e, g, e, g, e, e, e,
    e, e, e, e, e, e, e, e
    ]

sense.set_pixels(pet2)
--- /code ---
</div>

<div class="c-project-output">
![a picture of the changed cat on the full LED display](images/cat-2.png)
</div>

<div class="c-project-callout c-project-callout--tip">