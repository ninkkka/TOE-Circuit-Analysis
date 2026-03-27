# Обработка сигналов и математическое моделирование линейных электрических цепей

## Описание проекта
Данный проект представляет анализ поведения линейных электрических цепей при воздействии сигналов произвольной формы с применением численных, операторных и спектральных методов.

## Методы и инструменты
- **Численные методы:** метод Рунге-Кутты для решения системы уравнений состояния (MATLAB)
- **Операторный метод:** преобразование Лапласа, передаточные функции, анализ полюсов и нулей
- **Спектральный анализ:** ряды Фурье, амплитудные и фазовые спектры, оценка полосы пропускания
- **Частотный анализ:** АЧХ/ФЧХ, диаграммы Боде, характеристики фильтров

## Ключевые результаты
- Проанализировано поведение цепи при воздействии одиночного импульса и периодического сигнала
- Рассчитана передаточная функция, определены полюсы и нули системы
- Выполнена спектральная декомпозиция сигналов, оценены искажения на выходе
- Проведено сопоставление спектров входного и выходного сигналов для оценки качества фильтрации
- 
## Структура репозитория
TOE-Signal-Analysis/<br>
├── README.md<br>
├── Report.pdf # Пояснительная записка<br> 
└── Figures/  # Графики<br> 
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── bode_magnitude.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── bode_phase.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── input_spectrum_magnitude.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── input_spectrum_phase.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── output_spectrum_magnitude.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── output_spectrum_phase.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── input_discrete_magnitude.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── input_discrete_phase.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── fourier_approximation.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── output_discrete_magnitude.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── output_discrete_phase.png<br>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;└── output_waveform.png
