# deploy a yolov5 model using pytorch + flask

## start

```bash
$ FLASK_ENV=development FLASK_APP=app.py flask run
```
then, visit http://localhost:5000/ in your browser

## environments

- pytorch >= 1.6
- flask
- and [dependencies](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) required by [ultralytics/yolov5](https://github.com/ultralytics/yolov5)

## reference
- https://github.com/ultralytics/yolov5
- [Load YOLOv5 from PyTorch Hub ](https://github.com/ultralytics/yolov5/issues/36)
- https://github.com/avinassh/pytorch-flask-api-heroku
