# JavaScript Testing Library

Personal JavaScript testing library, light, easy to modify and test with.  
Displays the test results in the console log.

## Usage

Clone this repo and copy the `test.js` file in the project folder that you want to test.  
Create a `testSpec.js` file as per the example and test your functions.  
Set a `specRunner.js` file as per the example and open it in the browser to run the tests.

## Available commands

To test use:

```
expect(someThing)
```

And concatenate the matcher you want to use:

```
.toEqual(someThingElse)
.toInclude(someThingElse)
.toBe(someThingElse)
.notToInclude(someThingElse)
```
