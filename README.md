# TAKE HOME TASK

Imagine we have an image detection service, that takes an image and detects
if it contains a car.
The response format is like so:
```json
{
    "car": {
        "make": "Audi",
        "model": "A4",
        "generation": "IV (B8) facelift (2011-2015)",
        "years": "2011-2015",
        "prob": "100.00",
    },
    "color": {"name": "Black", "probability": 0.952},
    "angle": {"name": "Front", "probability": 1},
    "bbox": {"br_x": 0.8987, "br_y": 0.87, "tl_x": 0.1164, "tl_y": 0.1555},
}
```

Create a React component that gets an image from a user, and sends a REST API request
to the image detection service and then displays the result for the user
to see.

