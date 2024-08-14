#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    int a_tasks, b_tasks, tasks;
    scanf("%d", &a_tasks);
    scanf("%d", &b_tasks);
    scanf("%d", &tasks);

    // Максимальное количество студентов в первой команде
    int max_students_a = a_tasks;
    // Минимальное количество студентов во второй команде
    int min_students_b = (b_tasks + tasks - 1) / tasks; // округление вверх

    // Сравниваем количество студентов
    if (max_students_a > min_students_b) {
        printf("Yes");
    } else {
        printf("No");    
    }
    return 0;
}

/*
Студенты, разбившись на две команды, решали контест по программированию. Каждый студент решил не менее 1 и не более N задач. 
Известно, что первая команда суммарно решила A задач, а вторая — B задач.
Определите, могло ли быть в первой команде больше студентов, чем во второй.
*/
