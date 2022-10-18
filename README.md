# PingPongMultiThreadedProg


/*
 * CS 532: pingpong.c: play a game
 */

/*
 * pingpong: two threads take turns playing a game
 *
 * build like this ---> gcc -g -Wall -Werror pingpong.c -o pingpong -lpthread
 *
 * the code as-is has no synchronization, and so it fails.
 * the correct output should look like this:

 PING
 PONG
 PING
 PONG
 .
 .
 .

 * your assignment is to add synchronization so that the two threads take turns correctly.
 *
 */
