# Disaster Response Pipelines

--------------------------------------
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Example of some visual charts](#charts)
4. [View](#web)

## 1. Installation <a name="installation"></a>  
- Flask==0.12.2
- Flask-Bootstrap==3.3.7.1
- Flask-Cors==3.0.2
- Flask-HTTPAuth==3.2.3
- Flask-Login==0.3.2
- Flask-Mail==0.9.1
- Flask-Migrate==2.1.0
- Flask-Moment==0.5.1
- Flask-PyMongo==0.5.1
- Flask-Script==2.0.5
- Flask-SQLAlchemy==2.2
- Flask-Stormpath==0.4.8
- Flask-WTF==0.14.2
- python-dotenv==0.10.1
- pymysql==0.9.3
- gunicorn==19.9.0
- numpy==1.15.4
- pandas==0.23.4
- pyecharts==0.5.5
- The code should run with no issues using Python versions 3.*.

## 2. Project Motivation <a name="motivation"></a>  

Create an demo of a data presentation system for the product department, from which you can see some visual charts for each key link..

## 3. Visual charts  <a name="charts"></a>  
- The web app shows visualizations about some key indicators.
> ![example1](https://raw.githubusercontent.com/wjh2016/dashboard-demo/master/readme-img/example1.png)
> ![example2](https://raw.githubusercontent.com/wjh2016/dashboard-demo/master/readme-img/example2.png)

## 4. how to view the web app? <a name="web"></a>
There are two ways to view the web app:
1. You can click on this link[dashboard-demo](http://47.106.213.128:8000/home)
2. Run the following command in the app's directory to run the web app.  
>     `set FLASK_APP=flasky.py
>      set FLASK_CONFIG=production
>      flask run --host=0.0.0.0 --port=3001`
Then go to http://0.0.0.0:3001/

