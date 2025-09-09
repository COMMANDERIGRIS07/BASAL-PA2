#Course:ECE 2112: Advanced Computer Programming and Algorithms  
# BASAL-PA2 - Numerical python
#Name: Earl David M. Basal
#Section: 2ECE-C

#Problems

### 1. Normalization Problem
**Objective:** Perform data normalization on a randomly generated matrix.  

- Create a random **5x5 NumPy array** `X`.  
- Normalize the array using the formula:  

  \[
  Z = \frac{X - \bar{X}}{\sigma}
  \]

  where:
  - \( \bar{X} \) = mean of the array  
  - \( \sigma \) = standard deviation of the array  

- Save the normalized array as **`X_normalized.npy`**.  

---

### 2. Divisible by 3 Problem
**Objective:** Identify elements divisible by 3 in a matrix of squared integers.  

- Create a **10x10 NumPy array** containing squares of integers from 1 to 100.  
- Determine all elements divisible by 3.  
- Save the results as **`div_by_3.npy`**.  

---

## 📂 Output Files
- `X_normalized.npy` → Normalized version of the random 5x5 array.  
- `div_by_3.npy` → Elements from the 10x10 array divisible by 3.  

---

## ▶️ How to Run
1. Open the code in **Jupyter Notebook**.  
2. Run all cells.  
3. The `.npy` files will be generated in the same directory.  
4. To load the results later, use:
   ```python
   np.load("X_normalized.npy")
   np.load("div_by_3.npy")
