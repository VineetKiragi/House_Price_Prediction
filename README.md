![](Screenshot.PNG)

This data science project series walks through step by step process of how to build a real estate price prediction website. We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. Second step would be to write a python flask server that uses the saved model to serve http requests. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. During model building we will cover almost all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc. Technology and tools wise this project covers,

1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI

# Deploy this app to cloud (AWS EC2)

1. Create EC2 instance using amazon console
2. Now connect to your instance 
3. Setup nginx on EC2
4. Copy all your code to EC2 instance. Can be done either using git or copy files using winscp.
5. Once a connection is established to EC2 instance from winscp, now copy all code files into /home/ubuntu/ folder. 
6.  After copying code on EC2 server now point nginx to load our property website by default. For below steps,
7. Install python packages and start flask server
8. Load your cloud url in browser and this will be fully functional website running in production cloud environment



