## Animate the pet

You can create an animation by changing the displayed picture.

Create a `for` loop at the end of your program to quickly change between the two versions of the pet.

```python filename="main.py" line_numbers="true" line_number_start="35"
for i in range(5):
    sense.set_pixels(pet1)
    sleep(0.5)
    sense.set_pixels(pet2)
    sleep(0.5)
```

> [!TIP]
>
> To change the speed of the animation, you can change the `sleep` times.

> [!DEBUG]
>
> Check that you have 4 spaces of indentation on the lines beneath your `for` loop.

## Now run your code

Run your code and check that the two pictures play as an animation.

![An animation of the cat walking on the LED display.](images/animated-cat.gif)
