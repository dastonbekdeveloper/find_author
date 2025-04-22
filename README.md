# Muallifni Aniqlash Loyihasi

## 🎯 Maqsad
Berilgan matn asosida uning muallifini aniqlash. Model "EAP", "HPL", "MWS" (uchta muallif) dan birini aniqlaydi.

## 📦 Ma'lumotlar
Trening uchun `train.csv` fayli ishlatildi, har bir satrda matn va `author` mavjud.

## 🛠 Ishlatilgan texnologiyalar
- Python
- Scikit-learn
- NLTK
- XGBoost, Logistic Regression
- Tkinter (GUI)
- CountVectorizer + qo‘shimcha xususiyatlar (uzunlik va tinish belgilar soni)

## 🧠 Model
Final model `LogisticRegression` bo‘lib, quyidagi bosqichlarda tayyorlandi:
1. Matnni tozalash (stemming, lemmatizatsiya, stopword)
2. CountVectorizer orqali vektorlashtirish
3. Matnga 2 qo‘shimcha xususiyat qo‘shish:
   - belgilar soni
   - tinish belgilar soni
4. Logistic Regression bilan o‘rgatish

## 🚀 Ishlatish
1. `author_model.pkl` va `vectorizer.pkl` fayllarni mavjud joyga joylashtiring.
2. `main.py` faylini ishga tushuring.
3. Matnni kiriting va `Muallifni aniqlash` tugmasini bosing.

## 📈 Baholash
Model log_loss va Confusion Matrix orqali test qilindi.

## 📋 GitHub
Ushbu loyiha GitHub'da mavjud: [GitHub Repository](https://github.com/dastonbekdeveloper/find_author)


