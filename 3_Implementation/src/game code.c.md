#include "function.h"

 void game(){
 
 int i,countr=0;
     for(i=1;i<=3;i++)
     {
    
     switch(i)
		{
		case 1:
		printf("\n\nWhat is the unit of weight?");
		printf("\n\nA.kg\t\tB.g\n\nC.newton\t\tD.mg");
		if (toupper(getch())=='C')
			{
			    printf("\n\nCorrect!!!");countr++;
			    getch();

			    break;
}
		else
		       {
		           printf("\n\nWrong!!! The correct answer is C.newton");
		           getch();
                   score(countr);
		       break;
		       }

        case 2:
		printf("\n\n\nwhich of the following is non conventional energy source?");
		printf("\n\nA.coal\t\tB.petrol\n\nC.wind energy\t\tD.diesel");
		if (toupper(getch())=='C')
			{printf("\n\nCorrect!!!");countr++;
			getch();
			break;}
		else
		       {printf("\n\nWrong!!! The correct answer is C.wind energy");
		       getch();
               score(countr);
		       break;}

        case 3:
		printf("\n\n\nWhich animal laughs like human being?");
		printf("\n\nA.Polar Bear\t\tB.Hyena\n\nC.Donkey\t\tD.Chimpanzee");
		if (toupper(getch())=='B')
			{printf("\n\nCorrect!!!");countr++;
			getch();
			break;}
		else
		       {printf("\n\nWrong!!! The correct answer is B.Hyena");
		       getch();
               score(countr);
		       break;}

        case 4:
		printf("\n\n\nwhich of the following does contribute to the pollution in the water body?");
		printf("\n\nA.heavy metal \t\tB.ozone \n\nC.micro plastics \t\tD.pesticides");
		if (toupper(getch())=='B')
			{printf("\n\nCorrect!!!");countr++;
			getch();
			 break;}
		else
		       {printf("\n\nWrong!!! The correct answer is B.microplastics ");
		       getch();
               score(countr);
		       break;}

        case 5:
        printf("\n\n\ncalamine and sphalerite are the ores of..?");
        printf("\n\nA.iron\t\tB.zinc\n\nC.mica \t\tD.copper ");
        if (toupper(getch())=='B')
               {printf("\n\nCorrect!!!");countr++;
               getch();
                break;}
        else
		       {printf("\n\nWrong!!! The correct answer is B.zinc");
		       getch();
               score(countr);
		       break;}

        case 6:
		printf("\n\n\nSPHEREX mission has been launched by?");
		printf("\n\nA.A ROSCOMUS\t\tB.ISRO\n\nC.CNSA\t\tD.NASA");
		if (toupper(getch())=='D' )
			{printf("\n\nCorrect!!!");countr++;
			getch();
			break;}
		else
		       {printf("\n\nWrong!!! The correct answer is D.NASA");
		       getch();
               score(countr);
		       break;
               }

case 7:
		printf("\n\n\nWhat is the National Name of Japan?");
		printf("\n\nA.Polska\t\tB.Hellas\n\nC.Drukyul\t\tD.Nippon");
		if (toupper(getch())=='D')
			{printf("\n\nCorrect!!!");countr++;getch();
			 break;}
		else
		       {printf("\n\nWrong!!! The correct answer is D.Nippon");getch();
		       score(countr);
		       break;}

        case 8:
		printf("\n\n\nHow many times a piece of paper can be folded at the most?");
		printf("\n\nA.6\t\tB.7\n\nC.8\t\tD.Depends on the size of paper");
		if (toupper(getch())=='B')
			{printf("\n\nCorrect!!!");countr++;getch(); break;}
		else
		       {printf("\n\nWrong!!! The correct answer is B.7");getch();
		       score(countr);
		       break;}

        case 9:
		printf("\n\n\nwhich was the first living creature sent in space?");
		printf("\n\nA.dog\t\tB.cat\n\nC.monkey\t\tD.rat");
		if (toupper(getch())=='A')
			{printf("\n\nCorrect!!!");countr++; getch();
			break;}
		else
		       {printf("\n\nWrong!!! The correct answer is A.dog");getch();
		       score(countr);
		       break;}

        case 10:
		printf("\n\n\nWhich is the longest River in the world?");
		printf("\n\nA.Nile\t\tB.Koshi\n\nC.Ganga\t\tD.Amazon");
		if (toupper(getch())=='A')
			{printf("\n\nCorrect!!!");countr++;getch(); break;}
		else
		       {printf("\n\nWrong!!! The correct answer is A.Nile");getch();
               score(countr);
               break;
               }
               }
               }
               score(countr);
               }

	

