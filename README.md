s# PHYS 3120 - Homework Set #2

**Professor:** John Wise  
**Due Date:** Wednesday, January 29, 11:59 PM  
**Submission:** Submit your GitHub repository URL to Canvas. Ensure all code is uploaded as a single Jupyter notebook.

---

## Instructions

1. **Submission Requirements**
   - Your entire assignment should be uploaded as a single Jupyter notebook.
   - Use the provided template notebook available on Canvas as a starting point.
   - Include inline comments (`#`) or Markdown blocks to explain your code. Markdown is preferred for detailed explanations.

2. **Assignment Details**
   - The assignment includes three problems. There are no additional problems for graduate students.
   - The term “programs” refers to single or multiple code blocks in the Jupyter notebook.
   - Include all required materials specified with the `□✓` symbol at the end of each problem description.

---

## Problems Overview

### Problem 1: Altitude of a Satellite
Determine the altitude \( h \) for a satellite to achieve a circular orbit with a specified orbital period \( T \). The formula is:

\[
h = \left( \frac{G M T^2}{4 \pi^2} \right)^{1/3} - R
\]

#### Steps:
1. Write a program to:
   - Prompt the user for \( T \) (orbital period in seconds).
   - Calculate and display the corresponding altitude \( h \) (in meters).
2. Use the program to find altitudes for:
   - Geosynchronous orbit (\( T = 24 \) hours).
   - Orbit every 90 minutes (\( T = 5400 \) seconds).
   - Orbit every 45 minutes (\( T = 2700 \) seconds).
3. Answer the following questions:
   - What do you conclude from the 45-minute orbit calculation?
   - Why does a geosynchronous satellite orbit every 23.93 hours (sidereal day) instead of 24 hours? How does this affect the altitude?

#### Required Materials:
- Full commented code for part (a).
- Output of program runs for part (b) (three cases).
- Markdown explanations and answers for part (b) and part (c).

---

### Problem 2: Special Relativity - Time Dilation
Analyze the relativistic time dilation for a spaceship traveling at speed \( v \) to a planet \( x \) light-years away. The time dilation formula is:

\[
\Delta t' = \Delta t \sqrt{1 - \frac{v^2}{c^2}}
\]

#### Steps:
1. Write a program to:
   - Prompt the user for \( x \) (distance in light-years) and \( v \) (as a fraction of the speed of light \( c \)).
   - Calculate the travel time:
     - (a) In the rest frame of an Earth observer (\( \Delta t \)).
     - (b) As experienced by a passenger on the spaceship (\( \Delta t' \)).
2. Run the program for \( x = 10 \) light-years and \( v = 0.99c \).

#### Required Materials:
- Fully commented code.
- Program outputs for the given example.
- Ensure proper unit conversions are implemented and documented.

---

### Problem 3: Semi-Empirical Mass Formula
Calculate the nuclear binding energy \( B \) of an atomic nucleus using the formula:

\[
B = a_1A - a_2A^{2/3} - a_3\frac{Z^2}{A^{1/3}} - a_4\frac{(A - 2Z)^2}{A} + a_5A^{1/2}
\]

Where:
- \( a_1 = 15.67 \), \( a_2 = 17.23 \), \( a_3 = 0.75 \), \( a_4 = 93.2 \),
- \( a_5 = \begin{cases} 
0 & \text{if } A \text{ is odd}, \\
12.0 & \text{if } A \text{ and } Z \text{ are both even}, \\
-12.0 & \text{if } A \text{ is even and } Z \text{ is odd}.
\end{cases} \)

#### Steps:
1. Write a program to:
   - Accept inputs for \( A \) (mass number) and \( Z \) (atomic number).
   - Calculate:
     - (a) Total binding energy \( B \).
     - (b) Binding energy per nucleon \( B/A \).
2. Run the program for \( A = 58 \) and \( Z = 28 \) (expected \( B \approx 490 \) MeV).

#### Required Materials:
- Fully commented code.
- Output for the example calculation.

---

## Additional Notes
- Follow best practices for coding and commenting to ensure clarity and readability.
- Any assumptions or approximations should be documented in Markdown blocks.
- Ensure your notebook is properly organized and formatted for submission.

---
