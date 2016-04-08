# QuezX
Assignment for intern

Algorithm explanation:
    I have used an array which stores each skill with a specific index(array index) which is used for mapping it with specific skill.In another array which actually stores objects, each object contains an id(the one I previously defined in an array), count(number of times the skill has appeared in the whole json file with specific JOB ROLE which matches with user input), minsal(maximum of min_sal), maxsal(maximum of max_sal).
    The array with objects is sorted in descending order of count. For sorting I have used MERGESORT algorithm. Its time complexity is O(nlogn).For the ones with same number of count, I have used maxsal and further minsal as a sorting criteria. After that these are presented to user in scrollable view.
