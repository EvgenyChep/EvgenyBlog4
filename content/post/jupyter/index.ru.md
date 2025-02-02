---
authors:
- admin
categories: []
date: "2020-12-19T00:00:00Z"
draft: false
featured: false
image:
  caption: ""
  focal_point: ""
lastMod: "2020-12-19T00:00:00Z"
projects: []
subtitle: Система автоматической оценки стоимости автомобиля с пробегом
summary: Система автоматической оценки стоимости автомобиля с пробегом
tags: []
title: Система автоматической оценки стоимости автомобиля с пробегом 
---

Настоящее исследование затрагивает вопросы проектирования информационной системы для онлайн-оценки стоимости транспортного средства на основе машинного обучения. До недавнего времени вопрос оценки стоимости транспортного средства (ТС) был делегирован исключительно специалистам-оценщикам, которые являются экспертами в данном вопросе. Существенным недостатком такого подхода является значительные временные затраты и стоимость работ оценщиков. При этом часто у владельцев автомобилей возникает необходимость в быстрой и приблизительной оценке стоимости ТС по его основным характеристикам в режиме реального времени. С активным развитием методов и алгоритмов машинного обучения, появляется возможность создания экспертных систем, которые могут заменить специалистов при решении определенных задач. Одной из таких задач является оценка стоимости транспортного средства с приемлемым качеством в режиме реального времени. Для разработки сервиса онлайн-оценки стоимости ТС кроме создания самих алгоритмов оценки, требуется проектирование его высокоуровневой модели. Современная практика показывает, что такой подход наиболее эффективен для разработки сложно структурированных систем, требующих привлечения различных специалистов. В настоящем исследовании с одной стороны рассматривается высокоуровневая модель проектируемой системы в виде концептуальной и логической схемы, а с другой предлагается подход к автоматической оценке стоимости ТС на основе его характеристик с применением искусственной нейронной сети. В качестве средства создания модели информационной системы выбран унифицированный язык моделирования UML, который является промышленным стандартном.

## Оценка значений стоимости с использованием машинного обучения

Для проведения исследований по прогнозированию цены ТС была составлена база данных о подержанных автомобилях, содержащая более 200 записей. Для каждого автомобиля доступны следующие характеристики: марка автомобиля, год выпуска автомобиля, мощность двигателя, тип двигателя, объем двигателя, пробег транспортного средства, цена. Нужно совершить обработку данных и обучить сеть. Для начала нужно дать на вход массив исходных данных, на которых будет тренироваться сеть, потом добавим данные на выход. Нас интересует матрица с нелинейными рядами. Значения характеристик предварительно обрабатываются в форме, пригодной для дальнейшего анализа . 

![png](./index_1_0.png)

После того, как нейронная сеть будет обучена на обучающей выборке (наборе данных) сеть должна обладать хорошей обобщающей способностью. Те способностью нейронной сети воспроизводить входные данные при подачи на ее вход тех данных, которые участвовали в процессе обучения. Исходные набор обучающей выборки разбивается на три подмножества : training – обучение сети, validation – остановка обучения, test – общая оценка работы сети.

Читать полностью: https://www.elibrary.ru/item.asp?id=42760845



