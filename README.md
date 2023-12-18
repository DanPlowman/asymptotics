# The O, Omega, and Theta

Each row in the table below specifies two functions $f(n)$ and $g(n)$.
Fill in the *number* from this list that best describes their relationship:

1. $f(n)\in O(g(n))$, but $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Omega(g(n))$, but $f(n)\not \in O(g(n))$
1. $f(n)\not\in O(g(n))$, and $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Theta (g(n))$

I have done the first one for you, as an example.

| $f(n)=\ldots$              | compared to | $g(n)=\ldots$          |
|----------------------------|:-----------:|------------------------|
| $f(n)=n$                   | 1           | $g(n)=2n^2 + n$        |
| $f(n)= 10n + 3\log_{15} n$ |             | $g(n)= 4n - 2\log_2 n$ |
| $f(n) = 2n^5$              |             | $g(n) = 5n^2$          |
| $f(n)=\log_{10} \left(n^{10}\right)$ |  | $g(n)=n$ |
| $f(n)=\left\{ \begin{array}{cl} n^5 & \textrm{when $n<100$} \\
                                n^2 & \textrm{when $n\ge 100$}
        \end{array}\right.$ | | $g(n)=n^2$ |
| $f(n)=\left\{ \begin{array}{cl} n^2 & \textrm{when $n<42$} \\
                                n^8 & \textrm{when $n\ge 42$}
                \end{array}\right.$ | |
        $g(n)= \left\{ \begin{array}{cl} n^2 & \textrm{when $n$ is odd} \\
            n^{10} & \textrm{when $n$ is even}
                \end{array}\right.$ |
