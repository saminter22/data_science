# Прогноз увольнения сотрудников компании
## Описание проекта

Модель данных рассчитывается на основании анкетирования сотрудников компании: на входе данные по удовлетворенности сотрудника (на основании опросов) и показатели работы. На основании этих данных строится модель предсказания уровня удовлетворенности. Вторая часть расчетов - прогноз вероятности ухода. Исходя из этого кадровая служба может принять решение по заблаговременному поиску заменяющего кандидата на данную должность или предпринять усилия по удержанию сотрудника.

## Задача
Требуется спрогнозировать уход сотрудников для оперативного принятия мер службой HR, снижения оттока, превентивного фоормирования кадрового резерва на выбранные позиции, где вероятен отток. 

## Используемые библиотеки
sklearn.model_selection.train_test_split
sklearn.preprocessing: OneHotEncoder, OrdinalEncoder, StandardScaler, MinMaxScaler, LabelEncoder, PolynomialFeatures
sklearn.metrics: roc_auc_score, roc_curve, auc, make_scorer
sklearn.pipeline.Pipeline
sklearn.compose.ColumnTransformer
sklearn.tree: DecisionTreeClassifier, DecisionTreeRegressor
sklearn.neighbors.KNeighborsClassifier
sklearn.svm.SVC
sklearn.linear_model: LogisticRegression, LinearRegression, Ridge
sklearn.model_selection: GridSearchCV, RandomizedSearchCV
sklearn.impute.SimpleImputer 
phik
shap

В проекте используются датасеты с ресурсса https://code.s3.yandex.net/datasets/
