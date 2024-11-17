# Cow Cooling System

This project is a program designed to assist farmers by automatically triggering the cooling system for cows in the barn based on detected cow numbers.

## Customization

### Change Minimum Number of Cows:
To adjust the minimum number of cows required to start the cooling system, modify the following line of code:
```python
if cow_num > 0:
```
You can change the 0 to any other value to set a new minimum number of cows for triggering the system.

### Change Minimum Detection Percentage:
To modify the minimum detection percentage for a cow, change this line in the code:
```python
if name == 'cow' and value > 0.5:
```
Here, 0.5 represents the minimum detection confidence. Adjust this value to increase or decrease the sensitivity of the detection system.

### Current Output
For now, the program prints the results to the console in the following format:
```python
"There are 5 cows. Start cooling."
```
### Future Plans
The next step is to develop a GUI (Graphical User Interface) that will allow users to change the minimum number of cows and detection threshold without needing to modify the code directly.

### Notes
main file: yolo5-copy -> detect.py
