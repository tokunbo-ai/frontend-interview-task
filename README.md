# TAKE HOME TASK

Assume that we have an image detection service API, that takes an image of a car and returns the information about the car.  
An example response from the API is shown below:
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
From the response, we can see that the API returns the manufacturer of the car (Audi in the example), the model, color, etc.

## YOUR TASK
Create a React component that gets an image of a car from a user, and sends a REST API request
to the image detection service API and then displays the result for the user
to see.

## TASK CLARIFICATION
1. We are only interested in the frontend part of this service.
2. Essentially, your component should do the following:
 - allow the user to upload an image
 - display the result of the detection service to the user.
3. For the result shown to the user, we are interested in the manufacturer, model and color.
So an example display to the user can be:
**Your car is a black Audi A4.** Feel free to format it the way you want.

## Note
For simplicity, we want you to use the example response above, no matter what image the user uploads.
That is, **there is no need to make an API call**. Just hard-code the response above and use that
for any image that the user uploads. 


## Nice to have
- tests

## Submission guideline
- Create a github repository with your solution. The repository should include a README.
Feel free to explain any decisions you took in the README.

- Send the link to the repository to hr@tokunbo.org

