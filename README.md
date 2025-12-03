# project-15
Simple Alarm Clock Program
#include <stdio.h>
#include <unistd.h>

int main() {
    int seconds;

    printf("Set alarm (seconds): ");
    scanf("%d", &seconds);

    printf("Alarm set! Waiting...\n");
    sleep(seconds);

    printf("\n⏰ Alarm Ringing!\n");
    return 0;
}
