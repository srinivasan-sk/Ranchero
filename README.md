# Ranchero
from sklearn import tree
roomFeatures = [[20,3],[40,6],[50,8],[60,10],[100,14],[30,4]]
labels = ["exam-hall","exam-hall","class-room","class-room","seminar-hall","exam-hall"]
clf = tree.DecisionTreeClassifier()
clf = clf.fit(roomFeatures,labels)
print (clf.predict([[30,2]]))
