### input()

### Example

<iframe width="100%" height="450px" src="https://shaderpark.netlify.com/sculpture/-M21S8vSKMzSPfEQOJJ9?example=true&embed=true" frameborder="0"></iframe>

### Description
Creates an input slider defaulting to the provided starting value that ranges from the given minimum and maximum values. 

Behind the scenes a uniform is created for your input, which allows the slider to efficiently update new values.

### Syntax
```js
input(startValue, minValue, maxValue);

input(startValue);

input();
```

### Parameters
**startValue** Float: the initial value of.

**minValue** Float: the minimum range of the slider input. Defaults to 0.

**maxValue** Float: the maximum range of the slider input. Defaults to 1.0.