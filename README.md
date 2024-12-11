# BMI Calculator

This Python program calculates your Body Mass Index (BMI) based on your weight and height, and classifies your BMI into different categories.

## How to Use

1. **Input Your Name**: The program will prompt you to enter your name.
2. **Enter Your Weight**: Enter your weight in kilograms.
3. **Enter Your Height**: Enter your height in feet and inches. The program will automatically convert it into meters for BMI calculation.
4. **BMI Calculation**: The program will calculate your BMI using the following formula:
   ```
   BMI = weight(kg) / height(m)^2
   ```
   Where height is converted from feet and inches to meters (1 foot = 0.3048 meters).

5. **BMI Classification**: Based on your BMI, the program will print a classification message:
   - **Severe Thinness**: BMI < 16
   - **Moderate Thinness**: 16 ≤ BMI < 17
   - **Mild Thinness**: 17 ≤ BMI < 18.5
   - **Normal**: 18.5 ≤ BMI < 25
   - **Overweight**: 25 ≤ BMI < 30
   - **Obese Class I**: 30 ≤ BMI < 35
   - **Obese Class II**: 35 ≤ BMI < 40
   - **Obese Class III**: BMI ≥ 40

## Example

When you run the program, it will ask for your name, weight, and height:

```python
Input your name: John
Enter your weight in kilograms: 70
Enter your height in foot.inches: 5.9
```

The program will calculate and display your BMI and classify it based on the range:
```
Your BMI is 25.9
John, you are Overweight.
```

## Notes
- Ensure to enter your weight in kilograms and height in feet and inches.
- The program does not handle invalid inputs. Make sure you provide numeric values for weight and height to get accurate results.

## Conclusion
This simple BMI Calculator helps you determine your BMI and understand where you stand on the BMI scale, allowing you to monitor your health and wellness.

