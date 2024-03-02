## Flappy Bird AI with TensorFlow and Pygame

This project is a Python implementation of a simplified version of Flappy Bird, where "birds" use their own neural networks trained through genetic algorithm-based inheritance. Witness the evolution of strategies as the birds learn to navigate through obstacles!

### Features:
- Simplified Flappy Bird game environment.
- Birds with their own neural networks.
- Genetic algorithm for evolving bird behavior.
- Visual representation of bird training and gameplay using Pygame.

### Technologies Used:
- Python programming language.
- TensorFlow library for neural network implementation.
- Pygame library for interactive game graphics.

### How to Run:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Peczyn/FlappyBirdAI
   ```
   
2. **Install Dependencies:**
   ```bash
   cd FlappyBirdAI
   pip install -r requirements.txt
   ```
   or
   ```bash
   cd FlappyBirdAI
   pip3 install -r requirements.txt
   ```

4. **Run the Game:**
   ```bash
   python main.py
   ```
   or
   ```bash
   python3 main.py
   ```

6. **Interact:**
   - Watch as the birds evolve and learn to avoid obstacles.
   - Press `UpArrow` to jump (if you want to mess with the birds).

### Gameplay:
- Each bird has its own neural network controlling its actions.
- Birds are trained using a genetic algorithm based on their performance.
- The best-performing bird from each generation passes its genes to the next generation.
- You can track the current score, best score and generation as the birds evolve.

### Example:
Here's how to interact with the game:
1. Watch as the birds automatically learn to play the game.
2. Witness the evolution of bird strategies over generations.

<img width=32% alt="Menu1" src="https://github.com/Peczyn/FlappyBirdAI/assets/142744067/a6ee8ca8-d8b0-42b0-aa64-58aca2f12473">
<img width=32% alt="Menu2" src="https://github.com/Peczyn/FlappyBirdAI/assets/142744067/2ccd5b14-14a8-4269-b314-047ef0861f7a">
<img width=32% alt="Terminal2" src="https://github.com/Peczyn/FlappyBirdAI/assets/142744067/9f135523-be46-40d2-a157-8cef4d4dba84">


### Perfect AI:
It takes about 20-60 generations of 100 birds each to find the perfect one but sometimes it could take longer. Each generation is created by taking the brain of the smartest bird (of all time) and then making similiar copies of it. The better the bird was the smaller the brain changes are. The more the birds each generation the faster the AI learns.

<img width=45% alt="Terminal1" src="https://github.com/Peczyn/FlappyBirdAI/assets/142744067/857ed701-2737-45e4-9951-cdb385a17024">
<img width=45% alt="Rozwiazanie1" src="https://github.com/Peczyn/FlappyBirdAI/assets/142744067/10739068-9e14-4720-890f-e20d972c683d">


### Contributions:
Contributions to this project are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to open an issue or submit a pull request.

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
