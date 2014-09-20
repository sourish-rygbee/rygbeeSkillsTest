# Question 1

Given two strings, reverse all the occurrences of second string in the first string.

* _Input_: Two strings
* _Output_: First string with every occurrence of second string reversed.

__Eg.__

* _Input_: `betty_botter_bought_a_bit_of_butter._the_butter_betty_botter_bought_was_a_bit_bitter`, `botter_bought`
* _Output_: `betty_thguob_rettob_a_bit_of_butter._the_butter_betty_thguob_rettob_was_a_bit_bitter`


# Question 2

Given two strings reverse, consider the second string as sequence of characters/deleimeters (partition points) and reverse each partition of the first string.

__Eg.__

* _Input_: `A small man can cast a very big shadow.`, `mtd`
*  Output : `s Am llamsac nac natahs gib yrev a d.wo`
* _Highlighted delimeters_:
    * _Before reversal_: A s`m`all `m`an can cas`t` a very big sha`d`ow.
    * _After reversal_: s A`m` lla`m`sac nac na`t`ahs gib yrev a `d`.wo
