## Discussion

### 1. Play with your sorting hat. Are all 10 questions important to create the sorting hat? If you were to remove some questions to improve user experience, which questions would you remove and justify your answer?
**Answers:**  
Not all 10 questions are equally important for creating the sorting hat. To enhance user experience, I would consider removing the following:
- **Q6: What to do with a mystery book?** — This question may be too abstract, and its options could be interpreted differently by users.
- **Q7: Preferred pet?** — While fun, this question may not correlate strongly with personality traits and can be replaced by more behavior-focused questions.

---

### 2. If you were to improve the sorting hat, what technical improvements would you make?

#### How could you improve the model's accuracy or efficiency?  
**Answers:**  
- Collect more user data to better train and validate the model.
- Apply feature importance analysis to eliminate low-impact questions.
- Consider using model pruning or conversion tools (like TensorFlow Lite or Edge Impulse optimization) to reduce memory footprint for embedded deployment.

#### What additional sensors or hardware could enhance the user experience?  
**Answers:**  
- **Microphone**: Enable voice interaction for a more magical, immersive feel.
- **Vibration motor**: To give tactile feedback during selection or sorting.
- **Speakers or Bussers**: For audio feedback, such as spoken results or some music.

### Does decision tree remain suitable for your choice of new sensors?
**Answers:**
- **Decision trees** are good for simple inputs like button presses, but if we add new sensors like a **microphone**, **vibration motor**, or a **speaker**, decision trees may not be the best choice. 
- Decision trees work well for handling structured, discrete data (like button presses), but they struggle with continuous or unstructured data, such as sound or vibrations.
- If we want to use a **speaker** for audio feedback, a more flexible model like **TinyML** would be a better fit. TinyML can process the new sensor data on the device without needing powerful computing resources.
- For more dynamic sensors, models like **neural networks** or **random forests** could also provide more accurate predictions and handle complex inputs, making them a better choice than decision trees for this use case.

---
