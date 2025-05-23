# Deep Learning

Репозиторий содержит проекты по deep learning, целью которых являлось получение практических навыков работы в области машинного обучения.

---

## Проекты:

### 1. Классификация изображений с использованием нейронных сетей прямого распространения (FNN) - [ссылка на ноутбук](./1.%20Использование%20FNN%20для%20задач%20классификации.ipynb)

**Цель работы** - применение нейронных сетей прямого распространения (RNN) для задач классификации изображений из датасета `FER-2013`, который содержит изображения лиц людей с разметкой по эмоциям (грусть, радость, удивление и т.д.).

### 2. Интерполяция временных рядов с помощью RNN (LSTM) - [ссылка на ноутбук](./2.%20Интерполяция%20временных%20рядов%20с%20помощью%20LSTM.ipynb)

**Цель работы** -  применение рекуррентных нейронных сетей (RNN), а именно LSTM, для интерполяции временных рядов из датасета `Bitcoin Historical Data` (история изменения цен на биткоин) в условиях зашумленных данных и сравнение их с классическими методами.

### 3. Применение сети Хопфилда для ML-задач - [ссылка на ноутбук](./3.%20Применение%20сети%20Хопфилда%20в%20ML.ipynb)

**Цель работы** - реализация архитектуры сети Хопфилда для решения задач восстановления и классификации зашумленных изображений из датасета `MNIST` (подмножество из изображений цифр от 0 до 9).

### 4. Применение сети Кохонена для кластеризации - [ссылка на ноутбук](./4.%20Применение%20сети%20Кохонена.ipynb)

**Цель работы** - реализация архитектуры самоорганизующихся карт Кохонена (SOM) для задач кластеризации данных о продажах интернет-магазина из датасета "Online Retail".

### 5. Классификация изображений с помощью сверточных нейронных сетей (CNN) - [ссылка на ноутбук](./5.%20Классификация%20изображений%20с%20помощью%20CNN.ipynb)

**Цель работы** - применение сверточных нейронных сетей (CNN) для задач классификации изображений мусора из датасета "Garbage Classification" (классификация мусора). 

## Описание этапов работы и используемого стека в работах  
- Загрузка и предобработка данных  
- Нормализация изображений и разделение данных на тренировочную и тестовую выборки  
- Построение архитектуры моделей
- Обучение модели и анализ её точности на отложенной выборке
- Визуализация метрик точности модели
- Борьба с переобучением
- Выводы по проделанной работе

## Использованный стек
- `TensorFlow`, `Keras`, `Scikit-Learn` – разработка и обучение моделей  
- `NumPy`, `Pandas` – обработка данных  
- `Matplotlib`, `Seaborn` – визуализация результатов  
