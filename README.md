# Seq2Seq_Arithmetic
An implementation of sequence to sequence learning for performing arithmetic, there are four part

    * Adder

    * Subtractor

    * Combine adder and subtractor
    
    * Multiplicatoin

## Flow
*   Data representation

    char vocabulary: "0,1,2,3,4,5,6,7,8,9,+,-,*"
*   Data generation

    quetion ['36+152 ', '8+2    ', '915+0  ']

    answer  ['188 ', '10  ', '915 ']
*   Feature engineering

    Transfer the training sets to one-hot representation

    '+' [False True False False False False False False False False False False]

    '0' [False True True False False False False False False False False False]

    '8' [False False False False False False False False False False True False]
*   String matching
    *   Epoch 1 to Epoch 99

![image](https://github.com/hugikun999/Seq2Seq_Arithmetic/blob/master/pic/String_matching_1.PNG)

![image](https://github.com/hugikun999/Seq2Seq_Arithmetic/blob/master/pic/String_matching_99.PNG)

## [jupyter note](https://nbviewer.jupyter.org/github/hugikun999/Seq2Seq_Arithmetic/blob/master/Seq2Seq_Arithmetic.ipynb)