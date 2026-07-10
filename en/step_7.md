## Trigger the animation

You can make the animation run when the environment changes.

The `for` loop can sit inside a function. This can be **called** whenever the humidity changes.

```python filename="main.py" line_numbers="true" line_number_start="35"
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
```

> [!TIP]
>
> To change the humidity, use the slider.
>
> ![The humidity slider set to 45%.](images/humidity.png)

## Now run your code

Run your code, use the slider to raise the humidity above 50, and check that your animation starts.
