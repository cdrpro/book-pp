# Фильтры Bevel Effect и Emboss

### Фильтр Bevel Effect (Эффект скоса)

Следующий фильтр в группе **3D Effects** (Трехмерные эффекты) – фильтр **Bevel Effect** (Эффект скоса). Применение этого эффекта требует наличия маски. Если изображение или какая-то его часть не выделена, то Photo-Paint выведет окно с предупреждением (рис. 1).

![Фильтры Bevel Effect и Emboss](./9e134f99-6347-479e-9904-725abe7480b8.jpg)

Эффекты скоса позволяют создать видимость приподнятой поверхности путем скоса края редактируемой области. Например, эффекты скоса можно использовать для придания глубины тексту или его можно использовать для создания рамок. Диалоговое окно **Bevel Effect** (Эффект скоса) состоит из двух вкладок (рис. 2 и рис. 3).

![Фильтры Bevel Effect и Emboss](./81f1584e-830f-44bf-8f4d-4c34ce6dea83.jpg)

![Фильтры Bevel Effect и Emboss](./0f9ea8ad-9f09-4987-9892-8d19bbe6546d.jpg)

На вкладке **Bevel** (Скос) (рис. 2), задаются геометрические параметры эффекта, т. е. ширина и высота. Эти параметры задаются соответствующими ползунками **Width** (Ширина) и **Hight** (Высота). При этом параметр **Hight** (Высота) может принимать значения от 1 до 200, а **Width** (Ширина) от 3 до 100.  
Ползунок **Smoothness** (Сглаживание) придает более сглаженный вид полученному эффекту. Чем меньше значение параметра **Smoothness** (Сглаживание), тем более скошенными (более резкими) кажутся края (границы) скоса. Довольно хорошо начать экспериментировать с параметрами этого фильтра с текста. Создайте новый документ с белым фоном и крупным шрифтом наберите слово или фразу. Создайте из текста маску и примените эффект **Bevel Effect** (Эффект скоса). На тексте будет очень отчетливо видно влияние значения параметров.

Последний элемент управления на этой вкладке – флажок **Preserve interior** (Сохранять внутреннюю часть). Этот флажок отвечает за применение параметров освещения и текстуры для внутренней области скоса.  
В нижней части вкладки находится раскрывающийся список **Presets** (Заготовки) предоставляющий доступ к списку заготовок эффекта. Вы можете выбрать любую из них. Справа от списка расположены две кнопки в виде знаков «**+**» и «**—**», позволяющие сохранить пользовательские настройки в виде заготовки или удалить пользовательскую заготовку из этого списка. В случае сохранения заготовки, после нажатия кнопки со знаком «**+**» Photo-Paint выведет диалоговое окно **Save Preset** (Сохранение заготовки) (рис. 4), в котором вам будет предложено ввести название вашей заготовки в поле **Save new preset** (Сохранить заготовку как).

![Фильтры Bevel Effect и Emboss](./d2f1ab88-2e60-45ce-9820-e5fb289befb5.jpg)

Вкладка **Lightning** (Освещение) диалогового окна показана на рис. 3\. На этой вкладке расположены элементы управления эффектом освещения применяемого при создании скоса. С помощью ползунков **Brightness** (Яркость) и **Ambient** (Рассеянный) вы можете управлять яркостью части изображения, к которой применен эффект. Счетчики **Direction** (Направление) и **Angle** (Угол) предназначены для задания направления и угла падения света от мнимого источника света.

Вы можете эффекту назначить цвет с помощью раскрывающегося списка **Color** (Цвет) или текстуру, выбрав ее в раскрывающемся списке **Texture** (Текстура). Щелкнув на кнопке в виде открытой папки, вы можете загрузить другую текстуру в открывшемся диалоговом окне **Load Bevel Effect Texture Files** (Загрузка файлов текстуры эффекта скоса).  
Как и на вкладке **Bevel** (Скос), вкладка **Lightning** (Освещение) в нижней части имеет раскрывающийся список **Presets** (Заготовки), в котором вы можете выбрать одну из имеющихся в вашем распоряжении заготовок.

**Пример.**

Рассмотрим пример использования эффекта **Bevel Effect** (Эффект скоса). На рис. 5 показано исходное изображение.

![Фильтры Bevel Effect и Emboss](./33233ab9-c725-4809-bc66-ae0df0aae585.jpg)

Теперь создадим нечто наподобие рамки, как у картины. Для этого определимся с тем, какая часть изображения будет в нашей «картине». Все изображение помещать в рамку нет смысла. Выделим только центральную часть.  
Итак, наши действия:  
1\. На панели **Toolbox** (Набор инструментов) выберите инструмент **Rectangle** (Прямоугольник). На _Панели свойств_ отключите заливку, щелкнув кнопку **Disable fill** (Выключить заливку), также убедитесь, что кнопка **New object** (Создать объект) находится в нажатом состоянии. В счетчике **Outline width** (Толщина абриса) установите значение равным 15.  
2\. Нарисуйте прямоугольник по центру изображения.  
3\. Нажмите комбинацию клавиш **Ctrl + M**, чтобы создать из объекта маску (рис. 6).

![Фильтры Bevel Effect и Emboss](./b9603785-0f98-4831-9735-77985ae4fa4c.jpg)

4\. Выполните команду **Effects > 3D Effects > Bevel Effect** (Эффекты > Трехмерные эффекты > Эффект скоса).  
Значения параметров в диалоговом окне **Bevel Effect** (Эффект скоса) приведены на рис. 7 и рис. 8.

![Фильтры Bevel Effect и Emboss](./64a5fafd-ece8-4bd4-99ec-792530847724.jpg)

![Фильтры Bevel Effect и Emboss](./6265efda-72bb-4b29-bb17-f62c26af2d10.jpg)

4\. Теперь для удаления лишней части изображения на панели **Toolbox** (Набор инструментов) выберите инструмент **Crop** (Обрезка) и обрежьте части изображения выступающие за края рамки.

Окончательный вид изображения показан на рис. 9\. Естественно, как вы уже сами знаете, нужно удалить маску и объединить объект-прямоугольник с фоном.

![Фильтры Bevel Effect и Emboss](./eb97a8e8-6b71-4f4e-8f7b-06ffe666e802.jpg)

### Эффект Emboss (Рельеф)

Следующий фильтр в группе 3**D Effects** (Трехмерные эффекты) – фильтр **Emboss** (Рельеф).  
Фильтр **Emboss** (Рельеф) трансформирует изображение в рельеф, представляя детали изображения в качестве "рубцов и щелей" на плоской поверхности. Функция **Direction** (Направление) указывает на расположение источника света по отношению к изображению (в центре круга). В качестве цвета рельефа может использоваться исходное изображение, серый, черный цвет или цвета выбираемые из палитры представленной в виде раскрывающегося списка. Фильтр **Emboss** (Рельеф) лучше всего работает с изображениями средней и высокой контрастности. Диалоговое окно фильтра представлено на рис. 10.

![Фильтры Bevel Effect и Emboss](./3e985f59-55b7-49e1-a7bf-2e0d17619e34.jpg)

**Для применения эффекта рельефа:**

1\. Выполните команду **Effects > 3D Effects > Emboss** (Эффекты > Трехмерные эффекты > Рельеф).  
2\. Переместите ползунок **Depth** (Глубина) для задания величины рельефа вокруг краев. От этого зависит, насколько глубокими будут казаться щели и рубцы рельефа.  
3\. Щелкните по краю элемента управления **Direction** (Направление) для выбора местонахождения источника света.  
4\. Включите один из переключателей области **Emboss color** (Цвет рельефа) для задания цвета рельефного изображения.  
Ползунок **Level** (Уровень) служит для установки содержания исходных цветов в конечном изображении. Влияние значения параметра **Level** (Уровень) показано на рис. 11.

![Фильтры Bevel Effect и Emboss](./1635495c-77f4-4be2-8088-d1af18bccba2.jpg)

На рис. 11, слева направо: исходное изображение; значение параметра **Level** (Уровень) = 100 (по умолчанию); значение параметра **Level** (Уровень) = 300; значение параметра **Level** (Уровень) = 500\. Остальные параметры по умолчанию.