# STEPPER-MOTOR-INTERFACE
#include <LPC17xx.H>
void delay(unsigned int x);
main()
{
LPC_SC->PCONP |= (1 << 15); /* enable power to GPIO & IOCON */
LPC_GPIO0->FIODIR |= 0x00078000; /* Configure P0.15,P0.16,P0.17,P0.18 as
Outputs*/
LPC_GPIO2->FIODIR &= ~(1<<10); /* Configure P2.10 as Input */
while(1)
{
{
direction*/ direction*/ direction*/
direction*/
}
LPC_GPIO0->FIODIR =
0x00088000;
/* Write data for clock wise
delay(50000);
LPC_GPIO0->FIODIR = 0x00044000; /*
Write data for clock wise
delay(50000);
LPC_GPIO0->FIODIR= 0x00022000; /*
Write data for clock wise
delay(50000);
LPC_GPIO0->FIODIR =
0x00011000;
/* Write data for clock wise
delay(50000);
}
}
void delay(unsigned int x) /* Delay Routine */
{
for(;x>0;x--);
}
