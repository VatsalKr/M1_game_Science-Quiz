#include "unity.h"
#include "functions.h"

/* Modify these two lines according to the project */
#include "functions.h"
#define PROJECT_NAME "STEPIN_QUIZ-game"

/* Prototypes for all the test functions */
void show_record();
void reset_score();
void help();
void edit_score(float , char []);

/* Required by the unity test framework */
void setUp(){}
/* Required by the unity test framework */
void tearDown(){}

/* Start of the application test */
int main()
{
/* Initiate the Unity Test Framework */
  UNITY_BEGIN();

  /* Close the Unity Test Framework */
  return UNITY_END();
}


