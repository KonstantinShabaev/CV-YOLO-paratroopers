# Сегментация полей с использованием YOLOv8

Проект для автоматического определения и сегментации типов полей на изображениях с помощью YOLOv8 в режиме Instance Segmentation. Модель выделяет границы полей, присваивает им классы и визуализирует результат с подписями.

## Основные функции
- **Сегментация объектов**: Выделение точных границ полей с помощью масок.
- **Классификация**: Определение типа поля для каждого обнаруженного объекта.
- **Визуализация**: Наложение цветных контуров, подписей классов и масок на исходное изображение.
- **Гибкие настройки**: Контроль параметров детекции (пороги уверенности, IoU, размер изображения).

---

## 🛠 Установка
1. Склонируйте репозиторий:
```bash
git clone https://github.com/yourusername/field-segmentation.git
cd field-segmentation
