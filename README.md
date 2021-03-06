# hacktoberfest2k20

## Please help me with the given question below:

You have bought a new strange keyboard. When you press the **Numeric Lock** key, you cannot use any number. And sometimes the **Home** key, **End**  key or **Backspace**  key gets accidentally pressed.

You had to send an email to your supervisor. Since you were in hurry, you didn’t even notice that the text was messed up. After you sent the email, you knew that you need some help.

Given the text you wrote, print the text your supervisor will receive.

Note: The **Home** key changes the writing cursor's position to the beginning of the line, which means whatever after '<' goes before what is already written.

The **End** key changes the writing cursor's position to the end of the line, which means whatever after '>' goes after what is already written.

The **Backspace** key removes the previous character to the current position. And if there is nothing written, nothing happens.

The **Numeric Lock** key enables the numbers on the keyboard if they were disabled previously, and vice-versa. Initially, the **Numeric Lock** is on, that is you can use the numbers.

## Input Format

The only line of input consists of a string ,***S*** denotes the text contained in the email.

Constraints:
1<=|S|<=10^6

String contains Latin letters, underscores, digits, and four special characters:

1.**Home** key represented by '<'

2.**End** key represented by '>'

3.**Backspace** key represented by '*'

4.**Numeric Lock** key represented by '#'

Output Format

Print the text which your supervisor will receive.

Sample Input 0

HE*<LL>O

Sample Output 0

LLHO

Explanation 0

The first two letters will be written normally. So, the output is ***HE*** so far.

The third character indicates that ***Backspace*** key was pressed. Then, it deletes letter E. So, the output is ***H*** so far.

The fourth character indicates that ***Home*** key was pressed. Then, the typing cursor moves to the start of the text.

The next two letters will be written at the start, since the previous character was the ***Home*** key. So, the output is ***LLH*** so far.

The seventh character indicates that ***End*** key was pressed. Then, the typing cursor moves to the end of the text.

The next letter will be written at the end, since the previous character was the ***End***  key. So, the output is ***LLHO*** .


# Just add your file in respective language.
Thankyou.
