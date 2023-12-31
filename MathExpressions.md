# Example 1
[Example 1](https://github.blog/2022-05-19-math-support-in-markdown/)
## Markdown
When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$
## Expected Result
![Expected result](https://raw.githubusercontent.com/anvlasov/TextChat_fakeMsg/main/mathematical_expressions1.png "Expected result")


# Example 2: Writing inline expressions
[Example 2: Writing inline expressions](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions#writing-inline-expressions)
## Markdown
This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$
This sentence uses $\` and \`$ delimiters to show math inline:  $`\sqrt{3x-1}+(1+x)^2`$
## Expected Result
![Expected result](https://raw.githubusercontent.com/anvlasov/TextChat_fakeMsg/main/mathematical_expressions2.png "Expected result")


# Example 3: Writing expressions as blocks
[Example 3: Writing expressions as blocks]([https://github.blog/2022-05-19-math-support-in-markdown/](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions#writing-expressions-as-blocks))
## Markdown
**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
**The Cauchy-Schwarz Inequality**

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```
## Expected Result
![Expected result](https://raw.githubusercontent.com/anvlasov/TextChat_fakeMsg/main/mathematical_expressions3.png "Expected result")


# Example 4: Writing dollar signs in line with and within mathematical expressions
[Example 4: Writing dollar signs in line with and within mathematical expressions]([[https://github.blog/2022-05-19-math-support-in-markdown/](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions#writing-expressions-as-blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions#writing-dollar-signs-in-line-with-and-within-mathematical-expressions)))
## Markdown
Within a math expression, add a \ symbol before the explicit $.
This expression uses `\$` to display a dollar sign: $\sqrt{\$4}$

Outside a math expression, but on the same line, use span tags around the explicit $.
To split <span>$</span>100 in half, we calculate $100/2$
## Expected Result
![Expected result](https://raw.githubusercontent.com/anvlasov/TextChat_fakeMsg/main/mathematical_expressions4.png "Expected result")
