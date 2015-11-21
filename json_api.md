# Post Data
## Request
```json
{
    "workoutId": 1,
    "preTempsK" : [ 1, 2, 3, 4 ],
    "postTempsK": [ 1, 2, 3, 4 ],
    "timeSpentSeconds": 35,
    "points": [
        {
            "name": "leftCalf",
            "x": 1,
            "y": 2,
            "r": 1
        },
        {
            "name": "rightCalf",
            "x": 5,
            "y": 3,
            "r": 1,
        }
    ]
}
```

## Response
```json
{
    "endpoint": "/workouts/23",
    "prePoints": [
        {
            "name": "leftCalf",
            "x": 1,
            "y": 2,
            "r": 1,
            "maxTempK": 300,
            "q1TempK": 265,
            "q3TempK": 285,
            "minTempK": 250,
            "medianTempK": 275,
            "meanTempK": 270,
            "IQRK": 25,
        },
        {
            "name": "rightCalf",
            "x": 1,
            "y": 2,
            "r": 1,
            "maxTempK": 300,
            "q1TempK": 265,
            "q3TempK": 285,
            "minTempK": 250,
            "medianTempK": 275,
            "meanTempK": 270,
            "IQRK": 25,
        }
    ],
    "postPoints": [
        {
            "name": "leftCalf",
            "x": 1,
            "y": 2,
            "r": 1,
            "maxTempK": 300,
            "q1TempK": 265,
            "q3TempK": 285,
            "minTempK": 250,
            "medianTempK": 275,
            "meanTempK": 270,
            "IQRK": 25,
        },
        {
            "name": "rightCalf",
            "x": 1,
            "y": 2,
            "r": 1,
            "maxTempK": 300,
            "q1TempK": 265,
            "q3TempK": 285,
            "minTempK": 250,
            "medianTempK": 275,
            "meanTempK": 270,
            "IQRK": 25,
        }
    ],
}
```