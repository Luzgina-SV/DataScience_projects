# Разработка моделей предсказания поведения персонала для HR-компании #

**Цель исследования**
- разработка механизмов оптимизации управления персоналом для избежания финансовых потерь и оттока персонала

**Задачи исследования**
   1. построение модели прогноза уровня удовлетворенности сотрудника
   2. построение модели прогноза вероятности увольнения сотрудника
   3. разработка предложений по оптимизации HR-менеджмента на основе результатов прогноза

**Резюме**
1. определены модели наилучшим образом прогнозирующие уровень удовлетворённости сотрудников и вероятность их увольнения
2. на основе моделей разработаны рекомендации Заказчику, которвые позволят снизить отток персонала, тем  самым сократить финансовые потери

**Бибилиотеки, использованные в проекте**
- pandas
- numpy
- sklearn
  +  модули построения модели машинного обучения: DecisionTreeRegressor, DecisionTreeClassifier, KNeighborsClassifier, KNeighborsRegressor, SVC, SVR, LinearRegression, LogisticRegression, KFold, StratifiedKFold, DummyClassifier, DummyRegressor
  +  модули для создания пайплайна: Pipeline, ColumnTransformer
  +  модули для работы с пропусками, масштабирования и кодирования признаков: SimpleImputer, LabelEncoder, OneHotEncoder, OrdinalEncoder, StandardScaler, MinMaxScaler, RobustScaler
  +  модули автоподбора параметров: GridSearchCV, RandomizedSearchCV
  +  модули для расчета метрик: make_scorer, roc_auc_score, confusion_matrix
- shap
- phik
- matplotlib
- seaborn
