#include<stdio.h>
int main(){
    int i;
    int ans1,ans2,ans3,ans4,ans5;
    int p1,p2,p3,p4,p5,p6,p7,p8,p9,p10; //points
    int p01,p02,p03,p04,p05,p06,p07,p08,p09,p010;
    int t1,t2,t3; //total

    printf("Wlecome to the game\n\n");

    printf("> Press 7 to start the game\n");
    printf("> Press 0 to quit the game/n");

    scanf("%d",&i);

    if(i==7){
        printf("The game has started\n\n");
    }
    else if(i==0){
        printf("The game has ended\n\n");
    }
    else{
        printf("Invalid\n\n");
    }
    if(i==7){
        printf("\n1) Which one is the first search engine in internet?\n\n");
        printf("1) Google\n");
        printf("2) Archie\n");
        printf("3) Wais\n");
        printf("4) Altavista\n");

        printf("Enter your answer: ");
        scanf("%d",&ans1);

        if(ans1==2){
            printf("Correct Answer\n ");
            p1=5;
            printf("You have scored %d point\n", p1);
        }
        else{
            printf("Wrong Answer\n");
            p01=0;
            printf("You have scored %d point\n",p01);
        }
        printf("\n2) Which one is the first web browser invented in 1990?\n\n");
        printf("1) Internet Explorer\n");
        printf("2) Mosaic\n");
        printf("3) Mozilla\n");
        printf("4) Nexus\n");

        printf("Enter your answer: ");
        scanf("%d",&ans2);

        if(ans2==4){
            printf("Correct Answer\n");
            p2=5;
            printf("You have scored %d point\n", p2);
        }
        else{
            printf("Wrong Answer\n");
            p02=0;
            printf("You have scored %d point\n", p02);
        }
        printf("\n3) First computer virus is known as?\n\n");
        printf("1)Rabbit\n");
        printf("2) Creeper Virus\n");
        printf("3) Elk Cloner\n");
        printf("4) SCA Virus\n");

        printf("Enter your answer: ");
        scanf("%d", &ans3);
        
        if(ans3==2){
            printf("Correct Answer\n");
            p3=5;
            printf("You have scored %d point\n", p3);
        }
        else{
            printf("Wrong Answer\n");
            p03=0;
            printf("You have scored %d point\n", p03);
        }
        printf("\n4) Firewall in computer is used for?\n\n");
        printf("1) Security\n");
        printf("2) Data Transmission\n");
        printf("3) Monitoring\n");
        printf("4) Authentication\n");

        printf("Enter your answer: ");
        scanf("%d", &ans4);

        if(ans4==1){
            printf("Correct Answer\n");
            p4=5;
            printf("You have scored %d points\n",p4);
        }
        else{
            printf("Wrong Answer\n");
            p04=0;
            printf("You have scored %d point\n",p04);
        }
        printf("\n5) Which of the following is not a database management software?\n\n");
        printf("1) Mysql\n");
        printf("2) Oracle\n");
        printf("3) Cobol\n");
        printf("4) Sybase\n");

        printf("Enter your answer: ");
        scanf("%d",&ans5);

        if(ans5==3){
            printf("Correct Answer\n");
            p5=5;
            printf("You have scored %d point\n", p5);
        }
        else{
            printf("Wrong answer\n");
            p05=0;
            printf("You have scored %d point\n", p05);
        }
    }
    return 0;
}
