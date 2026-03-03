# Celsius to Fahrenheit Converter

A simple JavaScript utility function that converts temperatures from Celsius to Fahrenheit.

## Function

```js
function convertCtoF(celsius) {
  let fahrenheit = celsius * (9/5) + 32
  return fahrenheit
}
```

## Formula

```
°F = (°C × 9/5) + 32
```

## Usage

```js
convertCtoF(0);   // → 32   (Freezing point)
convertCtoF(100); // → 212  (Boiling point)
convertCtoF(37);  // → 98.6 (Body temperature)
```

## Parameters

| Parameter | Type   | Description                        |
|-----------|--------|------------------------------------|
| `celsius` | Number | The temperature value in Celsius   |

## Returns

Returns a `Number` representing the temperature converted to Fahrenheit.

## Examples

| Celsius | Fahrenheit | Description       |
|---------|------------|-------------------|
| -40     | -40        | Scales intersect  |
| 0       | 32         | Freezing point    |
| 20      | 68         | Room temperature  |
| 37      | 98.6       | Body temperature  |
| 100     | 212        | Boiling point     |
