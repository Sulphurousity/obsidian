Relevant PDFs: [[Non Traditional Composition _ Operation Notes _ Practice.pdf]]
The commonly memorized composition rule for limits is generally presented as:
$$\color{lightblue} \large \lim_{ x \to a } f(g(x))=f(\lim_{ x \to a } g(x))$$
provided that $\color{lightblue} \large \lim_{ x \to a } g(x)=L$ and $\color{lightblue} \large f(x)$ is continuous at $\large \color{lightblue} x=L$

However, If the $\large \color{lightblue} f(x)$ is not continuous at $\large \color{lightblue} x=L$ or if the limit of $\large \color{lightblue} g(x)$ does not exist at $\large \color{lightblue} x=a$, then we cannot apply the property.

This is also true with other conventional limit rules:
$$\large \color{lightblue} \lim_{ x \to a } (f(x)+g(x))=L_{1}+L_{2}$$
However, if $\large \color{lightblue} \lim_{ x \to a }f(x)$ or $\large \color{lightblue} \lim_{ x \to a }g(x)$ doesn't exist, then we cannot apply that property either.

If traditional limit rules do not apply, we can still use the left and right limits of a function as x approaches a to find if a limit exists or not.
$$\large \color{lightblue} if\lim_{ x \to a^- }f(x)=\lim_{ x \to a^+ } f(x)=L, then \lim_{ x \to a } f(x)=L$$
By exploring the right-hand and left-hand compositions or operations, we can often find if the limit being explored exists or not. 

Examples:
$$\large f(x)$$
![[Non-Traditional Composition Limits f(x)1.png#invert_B]]
$$\large g(x)$$
![[Non-Traditional Composition Limits g(x)1.png#invert_B]]

Find $\large \lim_{ x \to 1}f(g(x))$
$$\large 2$$
The answer is  $\large \color{lightblue} 2$ because $\large \color{lightblue} \lim_{ x \to 1 }g(x) = 0$ and $\large \color{lightblue} \lim_{ x \to 0 }f(x)=2$
> [!note] 
> The limit of the inner function becomes the value that x approaches in the outer limit

Find $\large \lim_{ x \to 2 }[f(x)\cdot g(x)]$
$$\large DNE$$
The answer is $\large \color{lightblue} DNE$ because $\large \color{lightblue} \lim_{ x \to 2 }f(x)$ does not exist because the left and right limits are not the same so the entire expression does not exist.

Find $\large \lim_{ x \to 0 }f(f(x))$
$$\large 0$$
The answer is $\large \color{lightblue} 0$ and not $\large \color{lightblue} DNE$ as one might expect because $\large \color{lightblue} \lim_{ x \to 0 }f(x) = 2$ but the value of $\large \color{lightblue} \lim_{ x \to 0 }f(x)$ approaches 2 from the bottom and since it is a cusp, the outer function will equal to $\large \color{lightblue} \lim_{ x \to 2^- }f(x)$ which is not the same as $\large \color{lightblue} \lim_{ x \to 2 }f(x)$ so the answer is 2
> [!note]
> If the function has a cusp at the value x approaches, and the function approaches from the bottom, the outer function will have an x value that approaches from the right (-). While, if the function approaches from the top, the outer function will have an x value that approaches from the left (+)