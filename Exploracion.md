Exploracion:

1. Age:La edad del empleado      
    1.1 Nulos: 0 ✔️
    1.2. Type object ❌
        ★ Formato Objet - Pasar a int64 ✔️
    1.3. Tipo de variable: Numérica ✔️ 

2. Attrition: Si el empleado ha dejado la empresa
    2.1. Yes: 259    
    2.2  No: 1355    
    2.3. 0 nulos 
    2.4. Type object ✔️
    2.5. Tipo de variable: Categórica ✔️
    ★ Interesa ver el patrón común de los empleados que dejan la empresa y contrastar estos valores con el patrón de los empleados que se quedan.

3. BusinessTravel:Frecuencia de los viajes    
    3.1. travel_rarely: 586
    3.2. travel_frequently: 165
    3.3. non-travel: 91
    3.4. Nulos: 772 ❌
        ★ Decidir lo que hacemos con esos nulos.
    3.5. Type object ✔️
    3.6. Tipo de variable: Categórica ✔️

4. DailyRate: La tarifa diaria
    4.1. Nulos: 0 ✔️
    4.2. Type object ❌
        ★ Formato Objet - Pasar a int❌
    4.3. Tipo de variable: Numérica ✔️

5. Department:El departamento
    5.1. Research & Development 196    
    5.2. Sales 91    
    5.3 Human Resources 15
    5.4 Nulos: 1312 ❌
        ★ Decidir lo que hacemos con esos nulos.    
    5.5 Type object ✔️
    5.6. Tipo de variable: Categórica ✔️

6. DistanceFromHome: La distancia desde el hogar 
    6.1 Nulos: 0 ✔️
    6.2 Type int64 ✔️
        ★ Pasar los valores negativos a positivo. ✔️
    6.3 Tipo de variable: Numérica ✔️

7. Education: Nivel de educación 
    7.1. 1: 180
    7.2. 2: 314
    7.3. 3: 621
    7.4. 4: 445
    7.5. 5: 54
    7.6. Nulos: 0 ✔️
    7.7. Type int64 ❌ 
        ★ Cambiar a object ? o mantener?❌ 
    7.8 Tipo de variable: Numérica    

8. EducationField: 
    8.1. Life Sciences 349
    8.2. Medical 276
    8.3. Marketing 104
    8.4. Technical Degree 69
    8.5. Other 59
    8.6. Human Resources 12
    8.7. Nulos 745 ❌
        ★ Decidir lo que hacemos con esos nulos.
    8.8. Type object ✔️
    8.9. Tipo de variable: Categórica ✔️ 

9. EmployeeCount: contar empleados
    9.1 Type int64 ✔️
    ★ Todos los valores son 1 - Eliminar Fila ✔️

10. EmployeeNumber: identificación único
    10.1. Nulos 431
        ★ Decidir lo que hacemos con esos nulos.
    ★  Pendiente ver filas duplicadas.
    10.2 Type object. 
        ★ Cambiar a a int ❌
    10.3 Tipo de variable: Numérica ❌

11. EnvironmentSatisfaction: Nivel de satisfacción entre el 1 y el 4
    11.1. 1: 298
    11.2. 2: 297
    11.3. 3: 459
    11.4. 4: 460
    11.5. Nulos 0 ✔️
    ★ datos erroneos: pendiente de decidir si los datos distintos de 0,1,2,3,4 cogemos el primer digito o eliminamos.
    11.6. Type object 
        ★ Cambiar a a int? ❌
    11.7 Tipo de variable: Numérica o categorica?❌

12. Gender: El género
    12.1. Hombre:971
    12.2. Mujer 643
    12.3. Nulos 0 ✔️
    12.4. Type int64 ❌
        ★ Cambiar a objet ✔️
    12.5. Tipo de variable: Categórica ✔️

13. HourlyRate: tarifa por hora
    13.1. Nulos: 0 ✔️
    13.2. Type object
        ★ Cambiar a a int? ❌
    13.3. Tipo de variable: Numérica ❌

14. JobInvolvement: Nivel de implicación
    14.1. 1: 89
    14.2. 2: 406
    14.3. 3: 955
    14.4. 4: 164
    14.5. Nulos: 0 ✔️
    14.6. Type int64 ❌
        ★ Cambiar a object ? ❌
    14.7. Tipo de variable: Numérica ❌

15. JobLevel: Nivel jerárquico
    15.1 1: 586
    15.2. 2: 597
    15.3. 3: 242
    15.4. 4: 113
    15.5. 5: 76
    15.6. Nulos: 0 ✔️
    15.7. Type int64 ❌
        ★ Cambiar a object ? ❌
    15.8. Tipo de variable: Numérica ❌

16. JobRole: El rol o puesto
    16.1. Nulos : 0 ✔️
    16.2. Type object✔️
    16.3. Tipo de variable: Categórica ✔️
    ★ Hay que unificar los nombres, mismo registro llamado de forma distintas (mANager, mAnaGeR, MANAgER, etc) ✔️

17. JobSatisfaction: Nivel de satisfacción
    17.1. 1: 317
    17.2. 2: 302
    17.3. 3: 481
    17.4. 4: 514
    17.5. Nulos: 0 ✔️
    17.6. Type int64 ❌
        ★ Cambiar a object ? o mantener? ❌
    17.7. Tipo de variable: Numérica ❌

18. MaritalStatus:  El estado civil
    18.1. divorced: 11
    18.2. Marreid: 35
    18.3. Divorced: 188
    18.4. Single: 325
    18.5. Married: 404 
    18.6. Nulos: 651 ❌
        ★ Ver como tratamos estos nulos.
    18.7. Type object✔️
    18.8. Tipo de variable: Categórica ✔️
    ★ Tenemos que unificar nombres y repetir recuento ✔️

19. MonthlyIncome: Ingresos mensuales
    19.1. Nulos 843 ❌
        ★ Ver como tratamos estos nulos.
    19.2. Type object 
        ★ Cambiar a int? ❌
    19.3. Tipo de variable: Numérica❌

20. MonthlyRate: Tasa mensual
    20.1. Nulos 
        ★ Ver como tratamos estos nulos.
    20.2. Type: int64✔️
    20.3. Tipo de variable: Numérica✔️

21. NUMCOMPANIESWORKED: Número de compañías en las que el empleado trabajó
    21.1. 0: 226
    21.2. 1: 573
    21.2. 2: 156
    21.3. 3: 169
    21.4. 4: 157
    21.5. 5: 66
    21.6. 6: 73
    21.7. 7: 84
    21.8. 8: 51
    21.9. 9: 59
    21.10. Nulos: 0 ✔️
    21.11. Type float64 ✔️
    21.12. Tipo de variable: Numérica✔️
    

 22. Over18: mayor de 18 años
    22.1. Y: 713, 
    22.2. Nulos 901 
        ★ Ver como tratamos estos nulos.
    ★ Comprobar que es coherente con la columna edad.
    22.3. Type int64 ✔️
    ELIMINADA ✔️

23. OverTime: empleado trabaja horas extras
    23.1. Yes: 256
    23.2. No: 682
    23.3. Nulos: 676
    23.4. Type: object✔️
    23.5. Tipo de variable: Categórica ✔️

24. PercentSalaryHike: El porcentaje de aumento salarial
    24.1. Nulos: 0.
    24.2. Type: int64✔️
    24.3. Tipo de variable: Numérica✔️

25. PerformanceRating: Calificación de rendimiento
    25.1. 3,0: 1215
    25.2. 4,0: 214
    25.3. Nulos: 195
    25.4. Type: object
        ★ Cambiar a int❌ 
    25.5 Tipo de variable: Numérica?❌

26. RelationshipSatisfaction: satisfacción en las relaciones interpersonales
    26.1. 1: 303
    26.2. 2: 339
    26.3. 3: 504
    26.4. 4: 468
    26.5. Nulos: 195
    26.6. Type: int64✔️
    26.7. Tipo de variable: Numérica✔️

27. StandardHours: horas estándar
    27.1. 80: 419
    27.2. Nulos: 1195
    27.3. Type: object
        ★ Cambiar a int❌ 
    27.4 Tipo de variable: Numérica?❌

28. StockOptionLeve: compra de acciones
    28.1. 0: 687
    28.2. 1:666
    28.3. 2: 172
    28.4. 3: 89
    28.5. Nulos: 0 ✔️
    28.6. Type: int64✔️
    28.7. Tipo de variable: Numérica✔️
    
29. TOTALWORKINGYEARS: Total de años de experiencia laboral
    29.1. Nulos: 526.
    29.2. Type: object
        ★ Cambiar a int❌ 
    29.3. Tipo de variable: Numérica?❌

30. TrainingTimesLastYear: empleado recibió capacitación el año pasado.
    30.1. 0: 60
    30.2. 1: 77
    30.3. 2: 598
    30.4. 3: 534
    30.5. 4: 137
    30.6. 5: 136
    30.7. 6: 72
    30.8. Nulos: 0 ✔️
    30.9. Type: int64✔️
    30.10. Tipo de variable: Numérica✔️

31. WORKLIFEBALANCE: Equilibrio entre trabajo y vida
    31.1. 1: 79
    31.2. 2: 359
    31.3. 3: 913
    31.4. 4: 155
    31.5. Nulos: 108
    31.6. Type: object, cambiar a int64❌
    31.7. Tipo de variable: Numérica?❌

32. YearsAtCompany: Años que el empleado ha trabajado en la empresa actual.
    32.1. Nulos: 0 ✔️
    32.2. Type: int64✔️
    32.3. Tipo de variable: Numérica✔️

33. YearsInCurrentRole: Años que el empleado ha estado en su puesto actual.
    33.1. 0: 4
    33.2. 1: 3
    33.3. 2: 11
    33.4. 3: 2
    33.5. 4: 3
    33.6. 6: 2
    33.7. 7: 5
    33.8. 11: 2
    33.9. 12: 1
    33.10 13:1
    33.11. Nulos: 1580
    33.12. Type: object
        ★ Cambiar a int❌  
    33.13. Tipo de variable: Numérica?❌

34. YearsSinceLastPromotion: Años desde la última promoción
    34.1. Nulos: 0 ✔️
    34.2. Type: int64✔️
    34.3. Tipo de variable: Numérica✔️

35. YEARSWITHCURRMANAGER: Años que el empleado ha estado bajo la supervisión del actual gerente.
    35.1. Nulos: 0 ✔️
    35.2. Type: int64✔️
    35.3. Tipo de variable: Numérica✔️
    
36. SameAsMonthlyIncome: Ingresos mensuales
    36.1. Nulos: 843.
      ★ Se elimina la columna ✔️

37. DateBirth: Año de nacimiento
    37.1. Nulos 0 ✔️
    37.2. Type: int64✔️
    37.3. Tipo de variable: Numérica✔️

38. Salary: Salario 
    38.1. Todos los valores 1000000000$ 
        ★ Se elimina la columna ✔️

39. RoleDepartament: El departamento y el rol
    39.1. Nulos: 1312
    39.2. Type: object✔️
    39.3. Tipo de variable: Categórica ✔️
    ★ Renombrar nombres: 

40. NUMBERCHILDREN: Número de hijos 
    40.1. Todos los valores nulos.
        ★ Se elimina la columna  ✔️
    
41. RemoteWork: teletrabajar 
    41.1. 0: 309
    41.2. 1: 360
    41.3. Yes: 295
    41.4. True: 345
    41.5. False: 305
    41.6. Nulos: 0 ✔️
    41.7. Type: object✔️
    41.8. Tipo de variable: Categórica ✔️
    ★ Unificar datos 0 y false - Yes, True y 1  ✔️



## Pendiente
1. Unificar Nombre de columnas.
2. Ver Filas repetidas.
3. Unificar nombre de las filas. dataframe[columna] = dataframe[columna].str.lower()