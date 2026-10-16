# aadit
# Pixelator

Pixelator is a simple calculator I made in Python. It's the start of my Python journey, and it's still a work in progress. I'm going to ship it now, but I'll be back to make it better, and maybe even build the hardware for it someday.

## What it can do

- Add, subtract, multiply and divide
- Trig functions (sin, cos, tan, csc, sec, cot) and their inverses, in degrees
- Powers and roots
- Logarithms (natural log or any base)
- A practice quiz with 10 random math questions
- A graphing calculator
- An AI problem solver (not done yet, it's just a placeholder for now)

## How to run it

You need Python 3. For the graphing part you also need matplotlib and numpy:

```
pip install matplotlib numpy
```

Then run the file and pick an option from the menu:

```
python3 pixelator.py
```

## Graphing

Type your function using `x`, like `x**2` or `np.sin(x)`. The graph goes from -10 to 10. It still needs some fine tuning, so don't take it too seriously yet.

## Heads up

This is version 1.0, so it has some rough edges. For example, a few undefined trig inputs (like tan of 90 degrees) aren't handled well yet.

Made by Aadit Sarangi. More features coming soon, so check back later!
