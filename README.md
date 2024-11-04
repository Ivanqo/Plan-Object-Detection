<h1>Разработка нейронной сети для работы с чертежами</h1>

<h2 align = "center">Plan-Object-Detection</h2>
<p>
    Модель машинного обучения, предназначенная для распознавания и перевода чертежей с PDF-файлов в DWG и другие форматы, используемые в CAD-программах, представляет собой инновационное решение для автоматизации процесса работы с технической документацией. Она позволяет быстро и точно преобразовывать чертежи из одного формата в другой, что значительно упрощает работу инженеров, архитекторов и дизайнеров.
</p>
<p>
    Эта модель обучена на большом наборе данных, включающем различные типы чертежей, и способна распознавать и анализировать сложные геометрические формы, линии и символы. Благодаря этому она обеспечивает высокую точность и качество перевода, минимизируя риск ошибок и искажений.
</p>

<h2 align = "center">Creating_dataset_BB</h2>
<p>Программа для преобразования набора картинок с XML-разметкой в датасеты в формате .tensor — это инструмент, который позволяет автоматически обрабатывать и систематизировать большие объёмы графических данных. Она широко используется в области машинного обучения и компьютерного зрения для разработки и тестирования алгоритмов распознавания образов, классификации объектов и других задач.
</p>
<p>
Программа обладает следующими функциями:
</p>

* **Загрузка изображений.** Программа позволяет загружать изображения вместе с их XML-разметкой, что упрощает процесс подготовки данных для обучения модели.
* **Преобразование данных.** Программа преобразует набор картинок с XML-разметкой в структурированные датасеты в формате .tensor. Это обеспечивает удобство использования данных в процессе обучения моделей машинного обучения.
<p>Использование программы для преобразования наборов картинок с XML-разметкой в формат .tensor позволяет ускорить процесс подготовки данных и повысить эффективность обучения моделей машинного обучения, особенно в задачах компьютерного зрения.</p>

<h2 align = "center">Training_iou_model</h2>

<p>
    Программа обучения модели локализатора объектов — это инструмент, который позволяет обучать модели машинного обучения для определения местоположения объектов на изображениях. Она широко используется в области компьютерного зрения и робототехники для разработки систем, способных автоматически определять расположение объектов в окружающей среде.
</p>

<p>
    <b>Основные функции программы:</b>
</p>
<ul>
    <li>Загрузка и обработка изображений с размеченными объектами.</li>
    <li>Обучение моделей на основе предоставленных данных.</li>
    <li>Оценка точности локализации объектов.</li>
    <li>Оптимизация параметров модели для повышения точности.</li>
</ul>

<p>
    Использование программы обучения модели локализатора объектов позволяет ускорить процесс разработки и тестирования систем компьютерного зрения, а также повысить их точность и надёжность.
</p>

<h2 align = "center">Classificator_training</h2>

<p>
    Программа обучения модели классификатора объектов — это инструмент, который позволяет обучать модели машинного обучения для определения и классификации различных типов объектов на изображениях. Она широко используется в области компьютерного зрения и робототехники для разработки систем, способных автоматически распознавать и классифицировать объекты в окружающей среде.
</p>

<p>
    <b>Основные функции программы:</b>
</p>
<ul>
    <li>Загрузка и обработка изображений с размеченными объектами.</li>
    <li>Обучение моделей на основе предоставленных данных.</li>
    <li>Оценка точности классификации объектов.</li>
    <li>Оптимизация параметров модели для повышения точности.</li>
</ul>

<p>
    Использование программы обучения модели классификатора объектов позволяет ускорить процесс разработки и тестирования систем компьютерного зрения, а также повысить их точность и надёжность. Программа может быть использована в различных областях, таких как автоматическое распознавание номерных знаков, идентификация лиц, классификация товаров в магазинах и т. д.
</p>

<h2 align = "center">Main_NN</h2>

<p>
    Программа Object Detection с подгрузкой обученных моделей — это инструмент, который позволяет использовать предварительно обученные модели для обнаружения и классификации объектов на изображениях. Она широко используется в области компьютерного зрения и робототехники для разработки систем, способных автоматически распознавать и определять местоположение различных типов объектов в окружающей среде.
</p>

<p>
    <b>Основные функции программы:</b>
</p>
<ul>
    <li>Загрузка и использование предварительно обученных моделей.</li>
    <li>Настройка параметров модели для адаптации к конкретной задаче.</li>
    <li>Запуск процесса обнаружения объектов на тестовых изображениях.</li>
    <li>Оценка точности и эффективности работы модели.</li>
</ul>

<p>
    Использование программы Object Detection с предварительно обученными моделями позволяет ускорить процесс разработки и тестирования систем компьютерного зрения, а также повысить их точность и надёжность. Это особенно полезно в случаях, когда требуется быстрое внедрение системы без необходимости обучения модели с нуля.
</p>

<h2 align = "center">Generating_image</h2> 
<p>
    Программа для генерации картинок с изображениями чертёжных осей — это инструмент, который позволяет создавать имитацию частей осей. Она идеально подходит создания обучающий выборки для модели классификатора и модели локализатора.
</p>
<p>
    С помощью этой программы вы сможете легко добавлять, редактировать и удалять оси на чертежах. Вы также сможете настраивать параметры осей, такие как размер, цвет и стиль, чтобы они соответствовали вашим требованиям. Программа поддерживает различные форматы файлов, что позволяет вам сохранять и открывать чертежи в разных программах.
</p>
