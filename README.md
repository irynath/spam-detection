# 📩 Визначення спаму в SMS

## 📌 Про проєкт
Цей проєкт визначає, чи є SMS-повідомлення спамом, за допомогою машинного навчання.

## 📊 Дані
Датасет: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

## 🧹 Очищення даних
- Видалення розділових знаків
- Переведення в нижній регістр
- Видалення стоп-слів

## 🤖 Моделі
| Модель | Точність |
|--------|----------|
| Naive Bayes | **96.6%** |
| Logistic Regression | 94.2% |

## 🏆 Висновок
Найкраще показала себе модель **Naive Bayes** з точністю 96.6%.

## 🚀 Запуск
1. Встановіть бібліотеки: `pip install pandas numpy matplotlib seaborn scikit-learn nltk`
2. Відкрийте `spam_detection.ipynb` у Jupyter Notebook
3. Запустіть усі клітинки (Kernel → Restart & Run All)

## 👩‍💻 Автор
[Грицюк Ірина]
