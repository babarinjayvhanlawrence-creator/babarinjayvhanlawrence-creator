## Babarin- Jayvhan Lawrence_LW1_Image_Classification.ipynb
## Google colab link https://drive.google.com/file/d/1qb4KuAieiQTNfTCXyJZxKqePvw9tBL8N/view?usp=sharing

## 1.What is the Fashion MNIST dataset?
## Answer: Fashion MNIST is a dataset of 70,000 grayscale images (size $28 \times 28$ pixels) of clothing and accessories.
It is used as a direct replacement for the original "handwritten digits" MNIST to test machine learning models. It features 10 categories: T-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.


## 2.Why do we normalize image pixel values before training?
## Answer: Raw pixel values range from 0 to 255 (black to white). We "normalize" them to a scale of 0 to 1 to make the math easier for the AI.Here is why we do it:
Speed: It’s easier and faster for the computer to process small, similar numbers ($0.1, 0.5, 0.9$) than large, fluctuating ones ($24, 188, 255$).
Stability: If the numbers are too large, the "gradient" (how the AI learns) can explode or crash. Keeping numbers small keeps the learning process steady.
Fairness: It ensures that every pixel is treated with equal importance from the start, preventing the model from getting "distracted" by high-contrast areas.


##3 

