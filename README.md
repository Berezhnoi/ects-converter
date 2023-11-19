
# ECTS Converter

Converts scores from the 100-point grading system to the ECTS format.


## Installation

Install ects-converter with npm

```bash
  npm install ects-converter
```
    
## Usage/Examples

```javascript
const ECTS = require('ects-converter');

const score = 85;
const ectsInstance = new ECTS(score);
const ectsValue = ectsInstance.ectsFromScore();

console.log(`ECTS value for score ${score}: ${ectsValue}`);
```

