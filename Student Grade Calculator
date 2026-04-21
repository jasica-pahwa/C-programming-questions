#include <stdio.h>
float calculatePercentage(int total){
    return total/5.0;
}
char getGrade(float percentage){
    if(percentage>=90) return 'A';
    else if(percentage>=75) return 'B';
    else if(percentage>=60) return 'C';
    else if(percentage>=40) return 'D';
    else return 'F';
}

int main(){
    int marks[5], total=0;
    printf("Enter marks for 5 subjects:\n");
    for(int i=0; i<5; i++){
        scanf("%d", &marks[i]);
        total+= marks[i];
    }
    float percentage = calculatePercentage(total);
    char grade = getGrade(percentage);
    printf("\nTotal=%d\n", total);
    printf("Percentage: %.2f\n", percentage);
    printf("Grade: %c\n", grade);

    return 0;
}