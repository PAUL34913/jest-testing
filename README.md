# Jest - JavaScript testing framework.

## Describing Tests

**English**

- I want to test a calculator.
- I am going to test the addition function.
- I want to get the result of 42.
- I expect 20 + 22 to eual 42.

**Jest**

    describe('calculator tests', () => {
        describe('addition tests', () => {
            test('should return 42 () => {
                expect(addition(20,22)).toBe(42);
            })
        });
    });