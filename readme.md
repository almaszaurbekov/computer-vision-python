# Computer Vision: Face Recognition
An python application that can recognize the faces of our classmates and give a small physical description:

## File description:
  - **master-file.ipynb** - основной фаил с кодом по распознаванию лиц людей
  - **api-tester.ipynb** - фаил для тестов различных API из Top Tens списка
  - **/data** - хранилище данных (samples, data_sets)
  - **/models** - модель для библиотеки dlib, которая распознает положение элементов лица
  - **/weights** - предобученная модель взятая из http://vintage.winklerbros.net/facescrub.html, обученная на более 100.000 лиц 530 людей.
  - **/images** - хранилище фотографий всех студентов из датасета
  - **/images** - хранилище фотографий всех студентов из датасета
  - **align.py**, **model.py**, **utils.py** - библиотеки, необходимые для правильной работы программы
  - **finalized_model.sav** - дообученная нами вручную модель лиц, дополненная лицами студентов. За основу взят датасет из папки **/weights**
  - **finalized_encoder.sav** - сохраненный encoder наших изображений
  
## How to install:
  in terminal run:
  ```python
  install python3

  pip install cmake
  pip install dlib
  pip install Keras
  pip install -r requirements.txt
  ```



