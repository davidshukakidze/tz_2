# ТЗ №2 ТП
![example workflow](https://github.com/arsbakh/tz2new/actions/workflows/ci.yml/badge.svg)
  
Файлы ***test***: проверяют, правильно ли работат код.  
Файлы ***testtime***: исполюзуются дл измерения скорости работы кода при увеличении количества чисел в файлах (результаты представлены на графике в файле ***chart***).  
В директории ***src*** расположен сам код, а также код, который измеряет скорость работы, зависящую от количества чисел. Там же расположен код для запусков тестов в Github Actions.  
Была сделана группа в Telegram с ботом, который отправлял **Все ок** в случае успешной проверки всех тестов, или же **Ошибку** с ее логом.
