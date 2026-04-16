# Assignment 2 Solutions

## Complete Solutions for Binary Sequences

This document provides detailed waveform encoding instructions for the six encoding schemes regarding binary sequences.

### 1. Unipolar Encoding
- **Description**: In unipolar encoding, all values are represented by non-negative voltages.
- **Waveform**: A constant positive voltage represents binary 1, and 0 volts represents binary 0.

### 2. Polar Encoding
- **Description**: In polar encoding, binary 1 and binary 0 are represented by equal positive and negative voltages, respectively.
- **Waveform**: Positive voltage for binary 1 and negative voltage for binary 0.

### 3. Bipolar Encoding
- **Description**: In bipolar encoding, binary 1 is represented by alternating positive and negative voltages, while binary 0 is represented by a zero voltage.
- **Waveform**: Positive voltage for binary 1 followed by negative voltage for subsequent binary 1s; 0 volts for binary 0.

### 4. 4B/5B Encoding
- **Description**: This scheme encodes 4 bits of data into 5-bit symbols to ensure sufficient transitions, enhancing clock recovery.
- **Waveform**: Each group of 4 bits is mapped to a unique 5-bit code that ensures bandwidth efficiency and transition density.

### 5. Differential Manchester Encoding
- **Description**: In differential Manchester encoding, a transition occurs at the middle of each bit period, with the presence of a transition indicating a binary 1.
- **Waveform**: Each bit period starts with a level transition; a transition at the beginning indicates binary 1, and no transition indicates binary 0.

### 6. Manchester Encoding
- **Description**: In Manchester encoding, each bit period is divided into two halves. A transition at the beginning symbolizes binary 1, and a transition at the middle symbolizes binary 0.
- **Waveform**: A rise from low to high in the first half of the bit period indicates a binary 1, while a fall from high to low indicates binary 0.

### Conclusion
The above waveform encoding schemes provide reliable means of encoding binary data, each with specific use cases and benefits depending on the application. Make sure to refer to specific waveform diagrams for better visualization of encoding schemes.
