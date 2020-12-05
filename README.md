# Проект 3: Путешествие по России

[ссылка на сайт](https://belkaksu.github.io/russian-travel/)

# Описание проекта

  Суть данной проекта заключалась в закреплении навыков работы с адаптивной версткой.


  В макете Figma были представлены 4 основных размера экрана различных устройств:
    *320px (мобильная версия);
    *768px (планшет);
    *1024px (ноутбуки);
    *1280px (экраны с большим расширением).

  Для более плавного расширения я добавила еще 2 медиа запроса.
    *425px;
    *680px.


  Для большей адаптивности я сверстала контейнер photo-grid используя свойство auto-fit.

  ```css
    .photo-grid {
      grid-template-columns: repeat(auto-fit, minmax(284px, 1fr));
  }
  ```

  Все картинки оптимизировала посредством сервиса (https://tinypng.com/).








