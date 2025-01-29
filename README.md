In the application, DecisionTreeClassifier, LogisticRegression, KNeighborsClassifier and SVM classifiers were compared.

Accuracy of the model improved with various parameters. Time to fit the model for SVM was higher compared to other models.

Model	Base_model_Accuracy
0	DecisionTreeClassifier	0.887432
1	LogisticRegression	0.887594
2	KNeighborsClassifier	0.887594
3	SVM	0.887675

	Model	best_score_with_CV	Train time	Best param
0	DecisionTreeClassifier	0.887239	[0.03394119739532471, 0.03200442790985107, 0.0...	{'model__criterion': 'entropy', 'model__max_de...
1	LogisticRegression	0.887205	[0.014447879791259766, 0.042438292503356935]	{'model__penalty': 'l2'}
2	KNeighborsClassifier	0.880337	[0.02899479866027832, 0.029509735107421876, 0....	{'model__n_neighbors': 2}
3	SVM	0.887205	[2.8975263357162477, 4.809007024765014, 3.0504...	{'model__C': 1, 'model__kernel': 'rbf'}
