## Welcome

CoviBuddy is your friendly Covid Web App aimed at providing vital features in one place.!

<hr>

<hr>

## Built With
* [Bootstrap](https://getbootstrap.com)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [OpenCV](https://docs.opencv.org/4.5.2/d6/d00/tutorial_py_root.html)


## Screenshots

### Covid Mask Detector
![Covid_Mask_Detector](https://github.com/sinking8/Covi-Buddy/blob/main/screenshots/face_mask.jpeg)

### Covid Tracker
![Covid_Mask_Detector](https://github.com/sinking8/Covi-Buddy/blob/main/screenshots/covid_tracker.png)

### Covid Detector Quiz
![Covid_Mask_Detector](https://github.com/sinking8/Covi-Buddy/blob/main/screenshots/quiz.png)


Project Structure
--------

  ```sh
  ├── Procfile
  ├── Procfile.dev
  ├── README.md
  ├── app.py
  ├── config.py
  ├── requirements.txt
  ├── covid_detector
  │   ├── saved_models
  │   ├── Covid_Detect.py
  │   ├── Mask_detect.py
  │   ├── Haarcascades
  ├── static
  │   ├── css
  │   ├── font
  │   ├── ico
  │   ├── img
  │   └── js
  └── templates
      ├── errors
      │   ├── 404.html
      │   └── 500.html
      └── pages
          ├── API.html
          └── CoviBuddy.html
          └── index.pug
          └── webcam.html
  ```


### Screenshots




### Quick Start

1. Clone the repo
  ```
  $ git clone https://github.com/sinking123/Covid-CoviBuddy.git
  $ cd CoviBuddy
  ```

2. Initialize and activate a virtualenv:
  ```
  $ virtualenv --no-site-packages env
  $ source env/bin/activate
  ```

3. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

5. Run the development server:
  ```
  $ python app.py
  ```

6. Navigate to [http://localhost:5000](http://localhost:5000)

