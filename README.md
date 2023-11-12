# Car Rental System - Testing README

## Testing Process

This README file provides an overview of the testing process conducted for the Car Rental System project.

### Static Analysis

Static analysis was performed using the SpotBugs tool. The goal was to identify bugs, security vulnerabilities, and coding errors in the source code. Three classes were analyzed, and a bug related to a redundant encryption operation was discovered. The recommendation is to remove or modify the code to improve code efficiency.

### Dynamic Testing

Dynamic testing was conducted using JUnit within the Eclipse environment. The AES class, responsible for encryption and decryption operations, was thoroughly tested. The testing revealed failures in all functionalities of the AES class, indicating potential implementation issues. Further investigation is required to identify the root causes and ensure the correct encryption functionality.

### Black Box Testing

Black box testing was carried out with a specific focus on input validation. Two test cases were created to assess the system's ability to handle invalid inputs, such as empty or incorrect data formats. The objective was to identify potential vulnerabilities or flaws in the input validation process.

## Recommendations

Based on the findings from the testing process, the following recommendations are provided:

- Remove or modify the redundant encryption operation identified in the static analysis to improve code efficiency.
- Conduct further investigation into the failures discovered in the AES class during dynamic testing and implement corrective measures to ensure proper encryption functionality.
- Strengthen input validation based on the results of the black box testing to enhance the system's security and robustness.

## Conclusion

The testing process conducted for the Car Rental System project aimed to improve the overall quality, security, and reliability of the system. By performing static analysis, dynamic testing, and black box testing with a focus on input validation, potential issues were identified and recommendations were made to address them effectively.
