# Optimización sin restricciones 
Este proyecto es parte de un trabajo del máster donde tenemos que implementar distintos métodos de optimización local en ``R``. La función con la que decidí trabajar es la siguiente:
$$f\left(x,y\right)=2\cos\left(\sqrt{x^2+y^2}\right)+\displaystyle\frac{\sqrt{x^2+y^2}}{6}-\ln\left(\sin\left(x-y\right)+x^2+3\right)$$
Dicha función tiene este aspecto:
![complicada1](https://github.com/Guille-Coru/Optimizacion_sin_restricciones/assets/168770171/2a6d6924-f84c-4b13-b027-816667e52d26)
## Indicaciones para el usuario
El programa es burdo y se mejorará proximamente. Si ahora un usuario quisiera usarlo tendrá que cambiar la función a minimizar manualmente dentro del código. Además tendrá que realizar cambios en la parte de los algoritmos que requieran de las derivadas parciales.
Un cambio a realizar es que un usuario pueda ejecutar este programa aportando de forma externa la función concreta que se quiera minimizar. 
