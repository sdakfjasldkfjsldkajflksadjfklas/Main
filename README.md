2022년 12월 28일 수요일
[김종진] [오후 6:03] [김현오] [오후 6:03] # TABLE FOOD

1. PRIMARY KEY (food_pk)
2. 음식의 이름 (food_name)
3. 그람 별 칼로리 (food_calorie)
4. 단위의 이름 (예: 개, 인분, 횟수...) (food_metricname)
5. 1단위의 그람수 (food_metricgrams)
6. 음식의 대분류 (EX. 구이, 국...) (food_category)
7. 그람 당 탄수화물 (food_carb)
8. 그람 당 지방 (food_fat)
9. 그람 당 단백질 (food_protein)
10. 그람 당 나트륨 (food_sodium)



# TABLE USER
1. PRIMARY KEY (USER_ID)
2. 나이 (USER_AGE)
3. 키 (USER_HEIGHT)
4. 몸무게 (USER_WEIGHT)
5. 성별 (USER_GENDER)
6. 현재 목표 칼로리수 (USER_CAL_GOAL)




# TABLE RECORD
1. PRIMARY KEY (RECORD_ID)
2. 날짜 (RECORD_DATE)
3. 먹은 음식 (RECORD_FOOD_ID)
4. 먹은 양 (RECORD_FOOD_AMOUNT)
