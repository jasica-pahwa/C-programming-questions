#include <stdio.h>
typedef enum{
     DEPOSIT=0,
    WITHDRAWAL=1,
    INQUIRY=2
 } TransactionType;

 typedef struct{
    int accountID;
    float balance;
 } Account;

 int main(){
    Account acc;
    int type;
    float amount;

    scanf("%d", &acc.accountID);
    scanf("%d", &acc.balance);
    scanf("%d", &type);
    scanf("%d", &amount);

    if(type==DEPOSIT){
        acc.balance+=amount;
        printf("Account %d: Deposited %.2f - New Balance: %.2f\n",
        acc.accountID, amount, acc.balance);
    }
    else if(type==WITHDRAWAL){
        if(amount>acc.balance){
            printf("Account %d: Insufficient Funds - Balance remains: %.2f\n",
            acc.accountID,acc.balance);
        }
        else{
            acc.balance-=amount;
            printf("Account %d: Withdrew %.2f - New Balance: %.2f\n",
            acc.accountID, amount, acc.balance);
        }
    } else if(type==INQUIRY){
        printf("Account %d: Current Balance is %.2f\n ",
        acc.accountID, acc.balance);
    }
    return 0;

        
    }


    
