# Error Calculation

## Error in $n$
We will calculate the error of $n $ considering Snell's formula because we used it in `Table - II` for calculating $ n $ for different light colors.
$$n = \frac{sin\left(\frac{A_p+D_{min}}{2}\right)}{sin\left(\frac{A_p}{2}\right)}$$
take `log` both sides and differentiate

$$\frac{\Delta n}{n} = cot\left(\frac{A_p+D_{min}}{2} \right) . \left( \frac{\Delta A_p + \Delta D_{min}}{2} \right) + cot\left(\frac{A_p}{2} \right). \left( \frac{\Delta A_p}{2} \right)$$


Since $A$ is given as a known quantity, we can take its error $\Delta A = 0$, so the final expression becomes

$$\frac{\Delta n}{n} = cot\left(\frac{A_p+D_{min}}{2} \right) . \left( \frac{\Delta D_{min}}{2} \right)$$

$\Delta D_{min}$ is the difference between two readings so that we can get two errors from two different readings, so $\Delta D_{min} = 2\times lc = 2\times 1^{'}  = \frac{2}{60} \times \frac{\pi}{180} \quad rad$

Find the error in the refractive index for only red color, i.e $\Delta n_R$. 

**NB** Remember that for error in $\omega$, you also need to calculate $\Delta n_B$ and $\Delta n_Y$, so if you are not running out of time and think that you can do all the calculation then find the error for them, if not then skip this part for the time being.

## Error in $A$
Since $A$ is the intercept of $n-1 \enspace vs. \enspace 1/\lambda^2$ graph, the error of $A$ can be taken as the smallest division in *y-axis*.

$\Delta A = sd_y \enspace (Graph)$ 

## Error in $B$

$$\frac{\Delta B}{B} = \frac{\Delta m}{m} + \frac{\Delta A}{A}$$

where $\Delta m = \frac{|m - m_1| + |m - m_2|}{2\sqrt{n_d}}$

$n_d$ is the no of data points.

## Error in $\omega$

$$\frac{\Delta \omega }{\omega} = \frac{\Delta n_B + \Delta n_R}{n_B - n_R} + \frac{\Delta n_Y}{\Delta n_Y - 1}$$

 *As per 2023-24 sem - I, error in $(\omega)$ is not necessary.*