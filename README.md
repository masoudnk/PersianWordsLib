Name: **PersianWords**  
Version: 0.1.6  
Summary:This library gives you some random words and paragraphs in persian language.  
Words list is very expensive and has a lot of different type of some words and how they are written.  
You can use this two methods to get required data:  
`from mnk_persian_words.persian_words import get_random_persian_paragraph, get_random_persian_word`  
import package and functions (because size of python file is large , some IDEs can not find functions in code completion.  
Also, if you see any errors in finding functions , just ignore it , or use `print(dir(persian_words))` to see functions names.)  
`get_random_persian_word(words_count: int =1)`  
Get a random words or as many as you want (less than 240,000!) as a string containing words seperated by space(" ") without trailing dot(".")  
`get_random_persian_paragraph(words_count: int = 5, paragraphs: int = 1)`  
Get a paragraph or as many as you want with each paragraph containing as many words as you want (less than 240,000!) as a string which **words seperated by space(" ")** and every paragraph before last paragraph has an **BreakLine("\n") at the end** also there is **no trailing dot**(".")   
Home-page: [https://github.com/masoudnk/PersianWordsLib](https://github.com/masoudnk/PersianWordsLib)  
Author: Masoud Najafzadeh Kalat  
Author-email: masoudnk2@gmail.com  
License: MIT License  
Words used in this library supported: [http://khodam.altervista.org/%D9%84%DB%8C%D8%B3%D8%AA-%D9%87%D9%85%D9%87-%DA%A9%D9%84%D9%85%D8%A7%D8%AA-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-%D9%85%D8%AC%D9%85%D9%88%D8%B9%D9%87-%DA%A9%D8%A7%D9%85%D9%84/]()
