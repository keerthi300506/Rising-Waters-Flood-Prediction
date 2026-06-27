# Project Testing

## Objective

The objective of testing is to verify that the Rising Waters AI Flood Prediction System performs correctly, provides accurate predictions, validates user input, and delivers reliable results through a user-friendly interface.

---

## Testing Environment

* Operating System: Windows 11
* Language: Python 3.x
* Framework: Flask
* IDE: Visual Studio Code
* Browser: Google Chrome
* Machine Learning Library: Scikit-learn
* Dataset: Flood Prediction Dataset

---

## Functional Test Cases

| Test Case | Description                    | Expected Result                       | Status |
| --------- | ------------------------------ | ------------------------------------- | ------ |
| TC-01     | Launch the application         | Home page loads successfully          | ✅ Pass |
| TC-02     | Enter valid feature values     | Prediction is generated               | ✅ Pass |
| TC-03     | Enter high-risk values         | High Flood Risk is displayed          | ✅ Pass |
| TC-04     | Enter moderate-risk values     | Moderate Flood Risk is displayed      | ✅ Pass |
| TC-05     | Click Reset button             | All input fields are cleared          | ✅ Pass |
| TC-06     | Display safety recommendations | Appropriate recommendations are shown | ✅ Pass |

---

## Validation Testing

| Input Condition        | Result                       |
| ---------------------- | ---------------------------- |
| Valid numerical values | Accepted                     |
| Empty input fields     | Validation message displayed |
| Decimal values         | Accepted                     |
| Large values           | Processed successfully       |

---

## Performance Testing

* Application loads successfully.
* Prediction is generated within a few seconds.
* User interface remains responsive.
* Model loads without errors.

---

## Compatibility Testing

| Browser        | Result |
| -------------- | ------ |
| Google Chrome  | ✅ Pass |
| Microsoft Edge | ✅ Pass |

---

## Testing Summary

All functional modules were tested successfully. The application correctly predicts flood risk, displays the prediction percentage, and provides appropriate flood safety recommendations. The Reset functionality, prediction logic, and interface were verified to work as expected.

### Overall Status

**Project Testing Successfully Completed.**

