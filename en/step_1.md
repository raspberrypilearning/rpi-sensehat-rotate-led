You can change the orientation of the LED matrix display on the Sense HAT. Use the `set_rotation()` method to rotate the screen one of four ways: by 0, 90, 180, or 270 degrees.

+ For example, to rotate your display by 180 degrees you'd use this code:

```python
sense.set_rotation(180)
```

+ You can also flip the image on the screen, either horizontally...

```python
sense.flip_h()
```

...or vertically.

```python
sense.flip_v()
```
