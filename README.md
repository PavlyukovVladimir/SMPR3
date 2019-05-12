<!-- комментарий-->
<!--ссылка на файл <a href='https://github.com/PavlyukovVladimir/SMPR/blob/master/scripts/NNBayes.R'>NNBayes.R</a>-->
<!--вставка картинки <img src="img/omega.jpg" alt="вероятность_собятия">-->
<base href="https://github.com/PavlyukovVladimir/SMPR2/blob/master/" ></base>
<a name="navigation"></a><!--Якорь для Навигации-->

## Навигация

<p>Решение оформлено в Jupyter notebook, страница с решением: <a href='Jupyter-notebook-notes/Metricheskiye_algoritmy_klassifikatcii.ipynb'>Metricheskiye_algoritmy_klassifikatcii.ipynb</a></p>
<p><a href="#mak"><h2>1.1. Метрические алгоритмы классификации</h2></a></p>
<p><a href="#bak"><h2>1.2. Байесовские алгоритмы классификации</h2></a></p>
<p><a href="#bak"><h2>1.3. Линейные алгоритмы классификации</h2></a></p>
<p><a href="#mvr"><h1>2. Методы восстановления регрессии</h1></a></p>
<p><a href="#fnw"><h2>2.1. Непараметрическая регрессия. Формула Надарая – Ватсона</h2></a></p>
<p><a href="#lowess"><h2>2.2. Метод LOWESS для непараметрической регрессии</h2></a></p>
<p><a href="#lr"><h2>2.3. Линейная регрессия</h2></a></p>
<p><a href="#gr"><h2>2.4. Гребневая регрессия</h2></a></p>
<p><a href="#lasso"><h2>2.5. Метод LASSO</h2></a></p>
<p><a href="#mgc"><h2>2.6. Метод главных компонент</h2></a></p>
<p><a href="#nlmr"><h2>2.7. Нелинейная модель регрессии</h2></a></p>
<p><a href="#ins"><h1>3. Искусственные нейронные сети</h1></a></p>
<p><a href="#bp"><h2>3.1. Метод обратного распространения ошибки (backpropagation)</h2></a></p>
<p><a href="#oss"><h2>3.2. Оптимизация структуры сети</h2></a></p>
<p><a href="#k"><h1>4. Кластеризация</h1></a></p>
<p><a href="#web"><h2>4.1. Тематическая кластеризация Web-документов</h2></a></p>
 
<h1 align="center">1. Алгоритмы классификации</h1><a name="ak"></a>

<h2>1.1. Метрические алгоритмы классификации</h2><a name="mak"></a>
<li>Используя готовые методы из библиотеки sklearn, применить алгоритмы классификации, основанные на методе ближайших соседей и методе парзеновского окна (использовать различные ядра) для классификации исходных данных.</li>
<li>Оптимальные параметры выбирать по критерию скользящего контроля.</li>
<li>Оценить качество построенных алгоритмов.</li>
<p></p>
<p>Решение оформлено в Jupyter notebook, страница с решением: <a href='Jupyter-notebook-notes/Metricheskiye_algoritmy_klassifikatcii.ipynb'>Metricheskiye_algoritmy_klassifikatcii.ipynb</a></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>1.2. Байесовские алгоритмы классификации</h2><a name="bak"></a>
<li>Используя готовые методы из библиотеки sklearn, применить байесовские алгоритмы классификации «наивный байес», линейный дискриминант Фишера и plug-in алгоритм для классификации исходных данных.</li>
<li>Оценить качество построенных алгоритмов.</li>
<p></p>
<p>Решение оформлено в Jupyter notebook, страница с решением: <a href='Jupyter-notebook-notes/Bayyesovskiye algoritmy klassifikatsii.ipynb'>Bayyesovskiye algoritmy klassifikatsii.ipynb</a></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>1.3. Линейные алгоритмы классификации</h2><a name="lak"></a>
<li>Используя готовые методы из библиотеки sklearn, применить линейные алгоритмы для классификации исходных данных.</li>
<li>Оценить качество построенных алгоритмов.</li>
<p></p>
<p>Решение оформлено в Jupyter notebook, страница с решением: <a href='Jupyter-notebook-notes/Linear classification algorithms.ipynb'>Linear classification algorithms.ipynb</a></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h1 align="center">2. Методы восстановления регрессии</h1><a name="mvr"></a>

<h2>2.1. Непараметрическая регрессия. Формула Надарая – Ватсона</h2><a name="fnw"></a>
<li>Реализовать метод ядерного сглаживания Надарая – Ватсона с гауссовским и квартическим ядрами.</li>
<li>Предоставить возможность настраивать все параметры алгоритма.</li>
<li>Сравнить SSE для гауссовского и квартического ядер.</li>
<li>Сделать выводы.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <a href='Jupyter-notebook-notes/nadaray_vatson.ipynb'>nadaray_vatson.ipynb</a></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.2. Метод LOWESS для непараметрической регрессии</h2><a name="lowess"></a>
<li>Реализовать алгоритм LOWESS для непараметрической регрессии и продемонстрировать его преимуществ по сравнению с обычным методом.</li>
<li>Предоставить возможность настраивать все параметры алгоритма.</li>
<li>Вывести значение функционала качества.</li>
<li>Сделать выводы.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.3. Линейная регрессия</h2><a name="lr"></a>
<li>Реализовать решение нормальной системы для задачи наименьших квадратов.</li>
<li>Вывести полученную функцию регрессии f1.</li>
<li>Применить сингулярное разложение, выбрать 2 компоненты, вывести функцию регрессии f2, отобразить ее в R2.</li>
<li>Сравнить качество f1 и f2.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.4. Гребневая регрессия</h2><a name="gr"></a>
<li>Реализовать метод гребневой регрессии.</li>
<li>Построить график зависимости функционала качества от параметра регуляризации.</li>
<li>Продемонстрировать преимущества метода.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.5. Метод LASSO</h2><a name="lasso"></a>
<li>Реализовать метод лассо Тибширани.</li>
<li>Построить график зависимости функционала качества от параметра регуляризации.</li>
<li>Продемонстрировать преимущества метода.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.6. Метод главных компонент</h2><a name="mgc"></a>
<li>Реализовать метод главных компонент.</li>
<li>Подобрать число компонент согласно относительной погрешности E(m).</li>
<li>Продемонстрировать преимущества метода.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>2.7. Нелинейная модель регрессии</h2><a name="nlmr"></a>
<li>Реализовать метод Ньютона–Рафсона или метод Ньютона-Гаусса</li>
<li>Вывести функцию регрессии.</li>
<li>Вывести значение функционала качества.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h1 align="center">3. Искусственные нейронные сети</h1><a name="ins"></a>

<h2>3.1. Метод обратного распространения ошибки (backpropagation)</h2><a name="bp"></a>
<li>Реализовать метод обратного распространения ошибки (backpropagation) для двухслойной/трехслойной сети.</li>
<li>Предоставить возможность задавать число слоев и нейронов в каждом слое.</li>
<li>Оценить качество работы нейронной сети.</li>
<li>Продемонстрировать преимущества метода.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h2>3.2. Оптимизация структуры сети</h2><a name="oss"></a>
<li>Реализовать программу для подбора оптимального числа слоев и нейронов в каждом слое нейронной сети с помощью динамического добавления нейронов и удаления избыточных связей.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>

<h1 align="center">4. Кластеризация</h1><a name="k"></a>

<h2>4.1. Тематическая кластеризация Web-документов</h2><a name="web"></a>
<li>Web-документы 3-х и более тематик по как минимум 20 документов по
каждой теме.</li>
<p></p>
<p><font color="green">Решение оформлено в Jupyter notebook, страница с решением: <strong>не решено</strong></p>
<p><a href="#navigation"><b>Вверх к навигации</b></a></p>
