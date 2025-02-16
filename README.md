# Sudoku Solver using OpenCV


## 📌 Overview
This project is a **Sudoku Solver** that uses **OpenCV** for image processing and **Python** for solving the puzzle using a backtracking algorithm. The program detects a Sudoku grid from an image, extracts the numbers, solves the puzzle, and overlays the solution back onto the image.

## 🚀 Features
- Detects and extracts Sudoku puzzles from images using OpenCV.
- Recognizes digits using OCR (Tesseract or a trained ML model).
- Solves the puzzle using a **backtracking algorithm**.
- Overlays the solution back onto the original image.
- Supports different Sudoku puzzle formats.

## 📂 Project Structure
```
📁 Sudoku-Solver-using-OpenCV
│── 📄 main.py               # Main script to run the solver
│── 📄 solver.py             # Sudoku solving algorithm
│── 📄 image_processing.py   # OpenCV functions for grid detection
│── 📄 digit_recognition.py  # OCR for recognizing digits
│── 📄 requirements.txt      # Dependencies list
│── 📁 images/               # Sample Sudoku images
│── 📁 output/               # Solved Sudoku images
```

## 🛠️ Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/ansh-sudan/Soduku-Solver-using-OpenCV.git
   cd Soduku-Solver-using-OpenCV
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the solver**
   ```bash
   python main.py --image images/sample_sudoku.jpg
   ```

## 🔧 Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib (for visualization)

## 🧩 How It Works
1. **Image Processing:** Uses OpenCV to detect the Sudoku grid, correct perspective, and extract digits.
2. **Digit Recognition:** OCR (Tesseract or a trained CNN model) is used to recognize numbers.
3. **Sudoku Solver:** Implements the backtracking algorithm to solve the puzzle.
4. **Overlay Solution:** The solution is mapped back onto the original image.

## 🎯 Example Output
| Input Image | Processed Grid | Solved Sudoku |
|------------|--------------|--------------|
| ![Input](images/sample_sudoku.jpg) | ![Processed](output/grid_detected.jpg) | ![Solved](output/solved_sudoku.jpg) |

## 📌 Future Improvements
- Improve OCR accuracy using a custom-trained CNN model.
- Add support for real-time Sudoku solving from camera input.
- Implement a GUI using Tkinter or PyQt.

## 🤝 Contributing
Feel free to fork this repository and submit a pull request with your enhancements!

## 📞 Contact
For any queries, reach out at **sudanansh1@gmail.com** or connect via **[LinkedIn]([https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/ansh-sudan-7aa596229/))**.
