### Постановка задачи

В файле evo_train.csv содержится 55861 строк с запросами по товарам, которые распределены по 29 категориям. В evo_test содержится 37240 строк, для каждой нужно определить категорию товара. Метрикой качества в задаче является "точность", вычисляемая по формуле:

$$\begin{equation*}
accuracy(y,y')=\sum_{k=0}^{n-1} [y_k = y'_k] 
\end{equation*}$$

