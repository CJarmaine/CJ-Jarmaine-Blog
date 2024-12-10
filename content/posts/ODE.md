Rearange for x and y terms
intergrate

Exam 3 question 1)
Solve separable differential equation $y'=y^2cos(x)$ , with the boundary condition $y(0)=1$.

$$y'=y^2cos(x)$$
$$\frac{dy}{y^2}=cos(x)dx$$
$$-\frac{1}{y}=sin(x)$$
$$y=\frac{1}{c-sin(x)}$$
solve for boundary $y(0)=1$
$$1=\frac{1}{c-sin(0)}$$
$$1=\frac{1}{c-0}$$
$$c=1$$
place into re-arranged
$$y=\frac{1}{1-sin(x)}$$
## Question b) 
Solve the differential equation $\frac{dy}{dx}=2x+4y$ by first using a transformation to convert to a separable differential equation.

### Steps
Rearrange to form
$$y'+p(x)y=Q(x)$$
Then find integrating factor 
$$I(x)=e^{\int{P(x)dx}}$$
Then rearrange to$$y=\frac{1}{I(x)}[\int{I(x)Q(x)dx+c}]$$
Rearranging the question requires moving 4y to the other side
$$y'-4y=2x$$
Finding the integrating factor
$$I(x)=e^{\int{-4xdx}}$$$$I(x)=e^{-4x}$$
Rearrange $$y=\frac{1}{e^{-4x}}[\int{e^{-4x}\times2xdx}+c]$$
$$y=\frac{1}{e^{-4x}}[\frac{1}{8}e^{-4x}(4x+1)+c$$
## Question 2
Solve the boundary value problem $3x^2e^ydx+x^3e^ydy=0, \quad y(2)=0$ by recognizing it as an exact differential equation, and using the technique of exact DEs.

$$3x^2e^ydx+x^3e^ydy=0$$$$\frac{\partial M}{\partial y}=3x^2e^ydx\quad\frac{\partial N}{\partial x}=3x^2e^y$$
$$\frac{\partial f}{\partial x}=3x^2e^y, \quad \frac{\partial f}{\partial y}=x^3e^ydy$$
$$f(x,y)=x^3e^y+g(y)$$
$$\frac{\partial f}{\partial y}=x^3e^y+g'(y)$$
