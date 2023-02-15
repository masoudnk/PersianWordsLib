Metadata-Version: 1

Name: **PersianWords**

Version: 0.1.6

Summary:This library gives you some random words and paragraphs in persian language.
Words list is very expensive and has a lot of different type of some words and how they are written.
You can use this two methods to get required data:

`from mnk_persian_words.persian_words import get_random_persian_paragraph, get_random_persian_word`

import package and functions (because size of python file is large , some IDEs can not find functions in code completion.
Also, if you see any errors in finding functions , just ignore it , or use print(dir(persian_words)) to see functions names.)

`get_random_persian_word(words_count: int =1)`
Get a random words or as many as you want (less than 240,000!) as a string containing words seperated by space(" ") without trailing dot(".")

`get_random_persian_paragraph(words_count: int = 5, paragraphs: int = 1)`
Get a paragraph or as many as you want with each paragraph containing as many words as you want (less than 240,000!) as a string which **words seperated by space(" ")** and every paragraph before last paragraph has an **BreakLine("\n") at the end** also there is **no trailing dot**(".") 

Home-page: https://github.com/NinjaSnail1080/akinator.py
Author: NinjaSnail1080
Author-email: innuganti.ashwin@gmail.com
License: MIT License

Copyright (c) 2019 NinjaSnail1080

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal