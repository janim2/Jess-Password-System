# Jess-Password-System

**Jess Password System (JPS) Demo Description:**

The **Jess Password System (JPS)** demo showcases an innovative approach to password security by combining traditional password input with **keystroke timing**. Instead of relying solely on the correct sequence of characters, the JPS system adds an additional layer of security by tracking how long each word is held down as part of the authentication process. 

### **How It Works**:
1. **Password Entry**:
   - Users type their password **word by word**, pressing either `space` or `Enter` to indicate the end of each word.
   - The system measures the **time (in whole seconds)** that each word's keys are held down.
   - These words and their respective timings are recorded and displayed in real-time to show how long the user pressed each word.

2. **Confirm Password**:
   - After entering the complete password, the user is prompted to re-enter it during the **confirmation phase**.
   - The confirmation process works similarly: the user types each word again, and the system records both the **words** and **timings** for comparison with the original input.

3. **Validation**:
   - The system checks if the **words** and their **timings** match exactly with the original password entry.
   - If there’s a **mismatch** in either the word or timing, an alert is triggered, and the process is reset.
   - If all words and timings are correct, the system confirms the password successfully.

### **Key Features**:
- **Time-based Security**: The JPS system tracks the precise duration for which each word is held, adding a behavioral biometric layer to traditional passwords.
- **Enhanced Authentication**: Even if an attacker knows the password, they would also need to match the exact typing rhythm and timing.
- **Real-time Feedback**: Users receive live feedback showing the time they held down each word, helping them understand how the system captures this additional data.
- **Password Confirmation**: The confirmation process requires users to type the password with the same timing, ensuring consistency and reducing the chances of false positives.

This demo is ideal for illustrating how combining **textual passwords** with **keystroke dynamics** can enhance security, making it more resistant to common password attacks such as brute force and keylogging.