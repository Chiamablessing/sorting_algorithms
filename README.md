# sorting_algorithms

This is an algorithm-based project written in C Programming Language, by Chiamaka Blessing

## Time complexity of algorithms

|Sorting algorithm   |Time complexity |
| -------- | ------- |
| Bubble sort | function that sorts an array of integers in ascending order using the Bubble Sort algorithm.   |
| Insertion sort | C function that sorts a listint_t doubly-linked list of integers in ascending order using the Insertion Sort algorithm.
Prints the list after each swap.   |
|  Quick sort  | C function that sorts an array of integers in ascending order using the Quick Sort algorithm.  |
| Shell sort | C function that sorts an array of integers in ascending order using the Shell sort algorithm. |
| Merge sort | C function that sorts an array of integers in ascending order using the Merge Sort algorithm. |

**Data Structures**

typedef enum kind_e
{
	SPADE = 0,
	HEART,
	CLUB,
	DIAMOND
} kind_t;

typedef struct card_s
{
	const char *value;
	const kind_t kind;
} card_t;

typedef struct deck_node_s
{
	const card_t *card;
	struct deck_node_s *prev;
	struct deck_node_s *next;
} deck_node_t;

