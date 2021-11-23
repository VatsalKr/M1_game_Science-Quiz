PROJ_NAME = QUIZ_GAME
SRC = 3_Implementation/src/functions.c\
3_Implementation/src/mainhome.c\
3_Implementation/src/home.c\ 
3_Implementation/src/game.c\

ifdef OS
   RM = del /q
   FixPath = $(subst /,\,$1)
   EXEC = exe
else
   ifeq ($(shell uname), Linux)
      RM = rm -rf
      FixPath = $1
	  EXEC = out
   endif
endif

all:
	gcc main.c $(SRC) -o $(call FixPath,$(PROJ_NAME).$(EXEC))

run: all
	./$(call FixPath,$(PROJ_NAME).$(EXEC))

clean:
	$(RM) $(call FixPath,$(PROJ_NAME).$(EXEC))

