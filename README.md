-fsanitize=thread, address, undefined

valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes
valgrind --tool=helgrind
valgrind --tool=drd
