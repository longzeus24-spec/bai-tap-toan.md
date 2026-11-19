### Bài I. Cho
$$
A = \begin{bmatrix} -1 & 2 \\ 4 & 1 \end{bmatrix}; \quad B = \begin{bmatrix} 1 & 0 & -2 \\ 3 & 1 & 2 \end{bmatrix}; \quad C = \begin{bmatrix} 1 & -2 & 3 \\ 5 & 1 & -1 \end{bmatrix}; \quad D = \begin{bmatrix} -2 \\ 2 \\ 1 \end{bmatrix}
$$

$AB$, $A(3B+C)$, $ABC$, $B^T A$, $BC^T$

---

## <u>LỜI GIẢI CHI TIẾT BÀI I</u>

**$AB$:**
$$
AB = \begin{bmatrix} -1 & 2 \\ 4 & 1 \end{bmatrix} \begin{bmatrix} 1 & 0 & -2 \\ 3 & 1 & 2 \end{bmatrix} = \begin{bmatrix} -1\cdot1 + 2\cdot3 & -1\cdot0 + 2\cdot1 & -1\cdot(-2) + 2\cdot2 \\ 4\cdot1 + 1\cdot3 & 4\cdot0 + 1\cdot1 & 4\cdot(-2) + 1\cdot2 \end{bmatrix}
$$
$$
\Longrightarrow AB = \begin{bmatrix} 5 & 2 & 6 \\ 7 & 1 & -6 \end{bmatrix}
$$

**$A(3B+C)$:**
$$
3B + C = \begin{bmatrix} 3 & 0 & -6 \\ 9 & 3 & 6 \end{bmatrix} + \begin{bmatrix} 1 & -2 & 3 \\ 5 & 1 & -1 \end{bmatrix} = \begin{bmatrix} 4 & -2 & -3 \\ 14 & 4 & 5 \end{bmatrix}
$$
$$
A(3B+C) = \begin{bmatrix} -1 & 2 \\ 4 & 1 \end{bmatrix} \begin{bmatrix} 4 & -2 & -3 \\ 14 & 4 & 5 \end{bmatrix} = \begin{bmatrix} -1\cdot4 + 2\cdot14 & -1\cdot(-2) + 2\cdot4 & -1\cdot(-3) + 2\cdot5 \\ 4\cdot4 + 1\cdot14 & 4\cdot(-2) + 1\cdot4 & 4\cdot(-3) + 1\cdot5 \end{bmatrix}
$$
$$
\Longrightarrow A(3B+C) = \begin{bmatrix} 24 & 10 & 13 \\ 30 & -4 & -7 \end{bmatrix}
$$

**$ABC$:**
* Kích thước ma trận $AB$ là $2 \times 3$, kích thước ma trận $C$ là $2 \times 3$. 
* Số cột của $AB$ ($3$) khác số hàng của $C$ ($2$).
$$
\Longrightarrow \text{Phép toán ABC không thực hiện được}
$$

**$B^T A$:**
$$
B^T = \begin{bmatrix} 1 & 3 \\ 0 & 1 \\ -2 & 2 \end{bmatrix}
$$
$$
B^T A = \begin{bmatrix} 1 & 3 \\ 0 & 1 \\ -2 & 2 \end{bmatrix} \begin{bmatrix} -1 & 2 \\ 4 & 1 \end{bmatrix} = \begin{bmatrix} 1\cdot(-1) + 3\cdot4 & 1\cdot2 + 3\cdot1 \\ 0\cdot(-1) + 1\cdot4 & 0\cdot2 + 1\cdot1 \\ -2\cdot(-1) + 2\cdot4 & -2\cdot2 + 2\cdot1 \end{bmatrix}
$$
$$
\Longrightarrow B^T A = \begin{bmatrix} 11 & 5 \\ 4 & 1 \\ 10 & -2 \end{bmatrix}
$$

**$BC^T$:**
$$
C^T = \begin{bmatrix} 1 & 5 \\ -2 & 1 \\ 3 & -1 \end{bmatrix}
$$
$$
BC^T = \begin{bmatrix} 1 & 0 & -2 \\ 3 & 1 & 2 \end{bmatrix} \begin{bmatrix} 1 & 5 \\ -2 & 1 \\ 3 & -1 \end{bmatrix} = \begin{bmatrix} 1\cdot1 + 0\cdot(-2) + (-2)\cdot3 & 1\cdot5 + 0\cdot1 + (-2)\cdot(-1) \\ 3\cdot1 + 1\cdot(-2) + 2\cdot3 & 3\cdot5 + 1\cdot1 + 2\cdot(-1) \end{bmatrix}
$$
$$
\Longrightarrow BC^T = \begin{bmatrix} -5 & 7 \\ 7 & 14 \end{bmatrix}
$$
