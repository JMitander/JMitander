

```javascript
function getMotivation(day) {
    if (day === "Monday") {
        throw new TypeError("Cannot read property 'motivation' of Monday. Please wait until Friday.");
    }
    if (day === "Saturday" || day === "Sunday") {
        return "Motivation level: Error 404. Weekend detected.";
    }
    return "Motivation level: High!";
```
