# 𝐌𝐗-𝟒𝟏𝟎𝟏-𝐆𝐫𝐨𝐮𝐩-𝟓-𝐏𝐫𝐚𝐭𝐢𝐜𝐞-𝐨𝐟-𝐓𝐞𝐱𝐭-𝐌𝐚𝐭𝐡-𝐚𝐧𝐝-𝐋𝐨𝐠𝐢𝐜𝐚𝐥-𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬
𝑨𝒖𝒕𝒉𝒐𝒓/𝒔: 𝘑𝘰𝘩𝘯 𝘙𝘦𝘺 𝘋𝘦𝘤𝘢𝘯𝘰, 𝘚𝘩𝘦𝘳𝘪𝘭𝘺𝘯 𝘎𝘰𝘯𝘻𝘢𝘭𝘦𝘴, 𝘢𝘯𝘥 𝘍𝘳𝘪𝘵𝘻 𝘎𝘢𝘣𝘳𝘪𝘦𝘭 𝘗𝘢𝘭𝘮𝘢

Basic Text, Math, and Logical Functions are highlighted in this section along with information on how to utilize and manipulate them in Microsoft Excel. Every definition of a function includes a reference to its syntax.

### 𝐀. 𝐓𝐄𝐗𝐓 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬

Excel is mostly about numerical data, but at times you can come across data that has too much text and that's the time when Text Functions in Excel will help you to simplify things easily.

Usage Scenarios:

1. Conversion from lowercase to uppercase.
2. Used to find the substring within a string.
3. Used to extract a substring from a string.
4. List specific words or characters from a string.


  A.1. LEN

> The Microsoft Excel TRIM function returns the length of the specified string.  

  𝑺𝒚𝒏𝒕𝒂𝒙

    = 𝘓𝘌𝘕( 𝘵𝘦𝘹𝘵)

  A.2. TRIM
  
>  The Microsoft Excel TRIM function returns a text value with the leading and trailing spaces removed. You can also use the TRIM function to remove unnecessary spaces between words in a string.

  𝑺𝒚𝒏𝒕𝒂𝒙

    = 𝘛𝘙𝘐𝘔( 𝘵𝘦𝘹𝘵)
  
  A.3. UPPER

>  The Microsoft Excel UPPER function allows you to convert text to all uppercase.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘜𝘗𝘗𝘌𝘙(𝘵𝘦𝘹𝘵)
  
  A.4. LOWER

 > The Microsoft Excel UPPER function allows you to convert text to all lowercase.

  𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘓𝘖𝘞𝘌𝘙(𝘵𝘦𝘹𝘵)
  
  A.5. PROPER

>  The Microsoft Excel PROPER function sets the first character in each word to uppercase and the rest to lowercase.

   𝑺𝒚𝒏𝒕𝒂𝒙

     = 𝘗𝘙𝘖𝘗𝘌𝘙(𝘵𝘦𝘹𝘵)
   
  A.6. SUBSTITUTE

>  The Microsoft Excel SUBSTITUTE function replaces one set of characters with another.

   𝑺𝒚𝒏𝒕𝒂𝒙

     =𝘚𝘜𝘉𝘚𝘛𝘐𝘛𝘜𝘛𝘌(𝘵𝘦𝘹𝘵,𝘰𝘭𝘥_𝘵𝘦𝘹𝘵,𝘯𝘦𝘸_𝘵𝘦𝘹𝘵, [𝘯𝘵𝘩_𝘢𝘱𝘱𝘦𝘢𝘳𝘢𝘯𝘤𝘦])
   
  Parameters
  
>  -> text - The original string to use to perform the substitution
>
> -> old_text - The existing characters to replace
>
> -> new_text - The new characters to replace old_text with.
>
> -> nth_appearance Optional It is the nth appearance of the old_text that you wish to replace. If this parameter is omitted, then every occurrence of old_text will be replaced with test text

  A.7. REPLACE

>  The Microsoft Excel REPLACE function replaces a sequence of characters in a string with another set of characters.

   𝑺𝒚𝒏𝒕𝒂𝒙
   
     =𝘙𝘌𝘗𝘓𝘈𝘊𝘌( 𝘰𝘭𝘥_𝘵𝘦𝘹𝘵, 𝘴𝘵𝘢𝘳𝘵, 𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘴, 𝘯𝘦𝘸_𝘵𝘦𝘹𝘵 )
   
  Parameters
  
> -> old_ text - The original string value.
>
> -> start - The position in old_text to begin replacing characters.
>
> -> number_of_chars - The number of characters to replace in old text
>
> -> new_text - The replacement set of characters


  A.8. FIND

>  The Microsoft Excel FIND function returns the location of a substring in a string. The search is case-sensitive

   𝑺𝒚𝒏𝒕𝒂𝒙
  
     =𝘍𝘐𝘕𝘋(𝘴𝘶𝘣𝘴𝘵𝘳𝘪𝘯𝘨,𝘴𝘵𝘳𝘪𝘯𝘨,[𝘴𝘵𝘢𝘳𝘵_𝘱𝘰𝘴𝘪𝘵𝘪𝘰𝘯))
   
  Parameters
  
>  ->  substring - The substring that you want to find
>
> -> string - The string to search within.
>
> -> start_position - Optional. It is the position in the string where the search will start. The first position is 1. If the start_position is not provided, the FIND function will start the search at the beginning of the string
  
  A.9. LEFT

>  The Microsoft Excel LEFT function allows you to extract a substring from a string, starting from the leftmost character.

   𝑺𝒚𝒏𝒕𝒂𝒙

     =𝘓𝘌𝘍𝘛(𝘵𝘦𝘹𝘵,[𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴])

  Parameters
 
>  -> text - The string that you wish to extract from.
>
> -> number_of_characters - Optional. It indicates the number of characters that you wish to extract starting from the leftmost character, If this parameter is omitted, only 1 character is returned.

  A.10. RIGHT

>  The Microsoft Excel RIGHT returns the last character or characters in a text string, based on the number of characters you specify.

   𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘙𝘐𝘎𝘏𝘛(𝘵𝘦𝘹𝘵,[𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴])
  
  Parameters
  
>  -> text - The string that you wish to extract from.
>
> -> number_of_characters - Optional. It indicates the number of characters that you wish to extract starting from the leftmost character. If this parameter is omitted, only 1 character is returned

  A.11. MID

>  The Microsoft Excel MID function extracts a substring from a string (starting at any position).

   𝑺𝒚𝒏𝒕𝒂𝒙

     =𝘔𝘐𝘋(𝘵𝘦𝘹𝘵,𝘴𝘵𝘢𝘳𝘵_𝘱𝘰𝘴𝘪𝘵𝘪𝘰𝘯,𝘯𝘶𝘮𝘣𝘦𝘳_𝘰𝘧_𝘤𝘩𝘢𝘳𝘢𝘤𝘵𝘦𝘳𝘴)
   
   Parameters
  
>  -> text - The string that you wish to extract from.
>
> -> start_position - The position in the string that you will begin extracting from. The first position in the string is 1.
>
> -> number_of_characters - The number of characters that you wish to extract. It is mandatory when the MID function is used as a Worksheet function, but optional in VBA. (if you omit this parameter in VBA, the MID function will return all characters after the start_position.)

  A.12. CONCATENATE

>   The Microsoft Excel CONCATENATE function allows you to join 2 or more strings together. 

   𝑺𝒚𝒏𝒕𝒂𝒙

     =𝘊𝘖𝘕𝘊𝘈𝘛𝘌𝘕𝘈𝘛𝘌(𝘵𝘦𝘹𝘵1, [𝘵𝘦𝘹𝘵2, … 𝘵𝘦𝘹𝘵_𝘯])
   
### 𝐁. 𝐌𝐀𝐓𝐇 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬

  B.1. ABS

> -> The ABS (Absolute Value) function in Excel returns the absolute value of a number. In other words: the ABS function removes the minus sign ( - ) from a negative number, making it

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘈𝘉𝘚(𝘯𝘶𝘮𝘣𝘦𝘳)
> ![ABS](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/67864e51-1c84-4402-ae69-dc6ba9762f2a)

  B.2. SIGN

> -> The Excel SIGN function returns the sign of a number as +1, 1, or 0.
>
> -> If the number is greater than zero, the SIGN function will return 1.
>
> -> If the number is equal to zero, the SIGN function will return 0.
>
> -> If the number is less than zero, the SIGN function will return 1

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘚𝘐𝘎𝘕(𝘯𝘶𝘮𝘣𝘦𝘳)
> ![SIGN](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/be2c573d-34fb-46af-a1f1-9c6e56ea3c1e)

  B.3. GCD

> -> The GCD (Greatest Common Divisor) function is used to get the greatest common divisor of two or more integers.
>
> -> The greatest common divisor is the largest positive integer that divides the numbers without a remainder.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘎𝘊𝘋(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![GCD](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/8ffae566-f28e-434d-ab0f-e8344bf9819b)

  B.4. LCM

> -> The LCM (Least Common Multiple) Function Calculates the least common multiple between two or more numbers.
>
> -> The least common multiple is the smallest integer that can be divided by all the numbers provided.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘓𝘊𝘔(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![LCM](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/e9161f74-b249-44ff-bd08-ec26b93b9150)

  B.5. POWER

> -> The Excel POWER function returns a number to a given power.
>
> -> The POWER function works like an exponent in a standard math equation.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘗𝘖𝘞𝘌𝘙(𝘯𝘶𝘮𝘣𝘦𝘳, 𝘱𝘰𝘸𝘦𝘳)
> ![POWER](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/006411e4-c607-495f-a4d4-459cf443a9d4)

  B.6. SQRT

> ->  The Excel SQRT function returns the square root of a positive number.
>
> ->  SORT returns an error if the number is negative.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘚𝘘𝘙𝘛(𝘯𝘶𝘮𝘣𝘦𝘳)
> ![SQRT](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/e438ac6c-3865-4409-b87f-6c3ca48d8e6c)

  B.7. QUOTIENT

> -> The Excel QUOTIENT function returns the result of integer division without remainder. 

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘘𝘜𝘖𝘛𝘐𝘌𝘕𝘛(𝘯𝘶𝘮𝘦𝘳𝘢𝘵𝘰𝘳, 𝘥𝘦𝘯𝘰𝘮𝘪𝘯𝘢𝘵𝘰𝘳)
> ![QUOTIENT](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/fd64aa14-7292-443a-be10-65f5c0d1bdaf)

  B.8. MOD

> -> The Excel MOD function returns the remainder of two numbers after division.
>
> -> For example, MOD(10,3) = 1.
>
> -> The result of MOD carries the same sign as the divisor.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘔𝘖𝘋(𝘯𝘶𝘮𝘣𝘦𝘳, 𝘥𝘪𝘷𝘪𝘴𝘰𝘳)
> ![MOD](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/ad2d1ac1-9d5c-4229-9daf-bc96664faf50)

  B.9. AVERAGE

> -> The Excel AVERAGE function calculates the average (arithmetic mean) of supplied numbers.
>
> -> AVERAGE can handle up to 255 individual arguments, which can include numbers, cell references, ranges, arrays, and constants.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘈𝘝𝘌𝘙𝘈𝘎𝘌(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![AGGREGATE - AVERAGE](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/bff06b4a-e27a-4cfa-8836-08198cb0bf6a)

  B.10. AVERAGE w/ criteria

> -> To calculate an average with criteria, use AVERAGEIF for single criteria or AVERGAEIFS for multiple criteria.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘈𝘝𝘌𝘙𝘈𝘎𝘌𝘐𝘍𝘚(𝘢𝘷𝘦𝘳𝘢𝘨𝘦_𝘳𝘢𝘯𝘨𝘦, [𝘤𝘳𝘪𝘵𝘦𝘳𝘪𝘢_𝘳𝘢𝘯𝘨𝘦1, 𝘤𝘳𝘪𝘵𝘦𝘳𝘪𝘢1, …)
> ![AVERAGE WITH CRITERIA](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/019aa37f-9fe3-46da-bf1d-eaa323d53ca7)

  B.11. COUNT
  
> -> The Excel COUNT function returns the count of values that are numbers, generally cells that contain numbers.
>
> -> Values can be supplied as constants, cell references, or ranges.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘊𝘖𝘜𝘕𝘛(𝘷𝘢𝘭𝘶𝘦1, 𝘷𝘢𝘭𝘶𝘦2, …)
> ![COUNT](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/3ccf5fbb-fa81-47a2-bbd8-1130d4801adc)

  B.12. COUNTA

> -> The Excel COUNTA function returns the count of cells that contain numbers, text, logical values, error values, and empty text (" ").
>
> -> COUNTA does not count empty cells.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘊𝘖𝘜𝘕𝘛𝘈(𝘷𝘢𝘭𝘶𝘦1, [𝘷𝘢𝘭𝘶𝘦2], …)
> ![COUNTA](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/8787c347-1040-4ca1-8c14-fb90e82bff30)

  B.13. COUNTBLANK

> -> The Excel COUNTBLANK function returns a count of empty cells in a range.
>
> -> Cells that contain text, numbers, errors, etc. are not counted
>
> -> Formulas that return empty text are counted.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘊𝘖𝘜𝘕𝘛𝘉𝘓𝘈𝘕𝘒(𝘳𝘢𝘯𝘨𝘦)
> ![COUNTBLANK](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/a5fcfcdb-b007-40c1-974b-ab237e25094a)

  B.14. MIN & MAX

> -> The MIN function can be used to return the smallest value from a set of data.
>
> ->  The MAX function returns the largest value from a supplied set of numeric values.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘔𝘐𝘕(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)

    =𝘔𝘈𝘟(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![MIN MAX](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/c594e629-bc9b-40c6-914e-fc4854b128a4)

  B.15. SUM
  
> -> The Excel SUM function returns the sum of the supplied.
>
> -> These values can be numbers, cell references, ranges, arrays, and constants, in any combination.
>
> Note: SUM can handle up to 255 individual arguments

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘚𝘜𝘔(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![SUM](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/4a74a70d-9c83-4e83-9a9f-65e0165ef782)

  B.16. MEDIAN

> -> The MEDIAN is the middle value in a group of numbers, separating the higher half of values from the lower half.
>
> -> For example, in the group of values (1, 2, 3, 4, 7} the median is 3. In the dataset (1, 2, 2, 3, 4, 7) the median is 2.5
>
> 4 Facts You Should Know About Excel Median
> 1. When the total number of values is odd, the Excel MEDIAN function returns the middle number in the data set. When the total number of values is even, it returns an average of the two middle numbers.
> 2. Cells with zero values (0) are included in the calculations.
> 3. Empty cells as well as cells containing text and logical values are ignored.
> 4. The logical values of TRUE and FALSE typed directly in the MEDIAN function's arguments are counted. For example, the formula MEDIAN(FALSE, TRUE,2,3,4) returns 2, which is the median of the numbers (0, 1, 2, 3, 4).

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘔𝘌𝘋𝘐𝘈𝘕(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![MEDIAN](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/8d3c5d25-9abb-4cc5-9215-f6d23fd19207)

  B.17. LARGE

> -> The Excel LARGE function returns numeric values based on their position in a list when sorted by value.
>
> -> In other words, it can retrieve "nth largest" values largest value, 2nd largest value, 3rd largest value, etc.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘓𝘈𝘙𝘎𝘌(𝘢𝘳𝘳𝘢𝘺, 𝘬)
> ![LARGE](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/c9a1f4a6-a72e-4e88-b70a-85dcd85fb2cf)

  B.18. SMALL

> -> The Excel SMALL function returns numeric values based on their position in a list ranked by value.
>
> -> In other words, it can retrieve "nth smallest" values smallest value, 2nd smallest value, 3rd smallest value, etc.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘚𝘔𝘈𝘓𝘓(𝘢𝘳𝘳𝘢𝘺, 𝘬)
> ![SMALL](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/e66533f8-a906-4729-85c6-ef2ffb72d9eb)

  B.19. PRODUCT

> -> The Excel PRODUCT function returns the product of numbers provided as arguments.
>
> -> The PRODUCT function is helpful when multiplying many cells together.
>
> -> The formula =PRODUCT(A1:A3) is the same as =A1*A2"A3.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘗𝘙𝘖𝘋𝘜𝘊𝘛(𝘯𝘶𝘮𝘣𝘦𝘳1, [𝘯𝘶𝘮𝘣𝘦𝘳2], …)
> ![PRODUCT](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/43adb2a8-1cd6-4ff4-9e37-2f3bc3b5149c)

  B.20. SUBTOTAL

> -> The Excel SUBTOTAL function returns an aggregate result for supplied values.
>
> -> SUBTOTAL can return a SUM, AVERAGE, COUNT, MAX, and others (see table below), and the SUBTOTAL function can either include or exclude values in hidden rows.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘚𝘜𝘉𝘛𝘖𝘛𝘈𝘓(𝘧𝘶𝘯𝘤𝘵𝘪𝘰𝘯_𝘯𝘶𝘮, 𝘳𝘦𝘧1, …)
> ![SUBTOTAL](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/d3b1a218-e608-436a-b362-afbcdadda106)

  B.21. CEILING & FLOOR
  
> -> The Excel CEILING function rounds a given number up to the nearest specified multiple.
>
> -> The Excel FLOOR function rounds a given number down to the nearest specified multiple.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘍𝘓𝘖𝘖𝘙(𝘯𝘶𝘮𝘣𝘦𝘳, 𝘴𝘪𝘨𝘯𝘪𝘧𝘪𝘤𝘢𝘯𝘤𝘦)

    =𝘊𝘌𝘐𝘓𝘐𝘕𝘎(𝘯𝘶𝘮𝘣𝘦𝘳, 𝘴𝘪𝘨𝘯𝘪𝘧𝘪𝘤𝘢𝘯𝘤𝘦)
> ![CEILING AND FLOOR](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/45ac9fad-c9cb-4491-ab2c-1d016d755272)

  B.22. EVEN & ODD
> EVEN  
> -> The Excel EVEN function returns the next even integer after rounding a given number up.
>
> -> The EVEN function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative)

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘌𝘝𝘌𝘕(𝘯𝘶𝘮𝘣𝘦𝘳)
> ![EVEN](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/88f098bc-15f8-4486-8645-a287f1e5eb3b)

> ODD
> -> The Excel ODD function returns the next odd integer after rounding a given number up.
>
> -> The ODD function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative).

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘖𝘋𝘋(𝘯𝘶𝘮𝘣𝘦𝘳)
> ![ODD](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/f4cffd2f-1971-4932-ba1f-1b767b30aa26)

  B.23. ROUND & TRUNC
>> ROUND
>> 
>> -> The Excel ROUND function returns a number rounded to a given number of digits.
>>
>> -> The ROUND function can round to the right or left of the decimal point.
>>
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘙𝘖𝘜𝘕𝘋(𝘯𝘶𝘮𝘣𝘦𝘳, 𝘯𝘶𝘮_𝘥𝘪𝘨𝘧𝘪𝘵𝘴)
>> ![ROUND](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/8edaa066-357d-45eb-9a83-5d8ddf34139a)

>> TRUNC
>> 
>> -> The Excel TRUNC function returns a truncated number based on an (optional) number of digits.
>>
>> -> For example, TRUNC(4.9) will return 4, and TRUNC(-3.5) will return -3.
>>
>> -> The TRUNC function does no rounding, it simply truncates all specified.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘛𝘙𝘜𝘕𝘊(𝘯𝘶𝘮𝘣𝘦𝘳, [𝘯𝘶𝘮_𝘥𝘪𝘨𝘧𝘪𝘵𝘴])
>> ![TRUNC](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/d343d793-03ff-4fe4-809b-43c026db5a36)

### 𝐂. 𝐋𝐨𝐠𝐢𝐜𝐚𝐥 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐬

A LOGICAL FUNCTION is one that evaluates an expression and returns a Boolean result.

For example, imagine a series of cells that represent employees' last names. If you are interested to know which cell doesn't have a name, you can use a function. On the other hand, imagine you have a cell that is supposed to indicate when must you receive a discount, you can use a conditional function to check it.

Most, if not all, logical functions check a condition and render a result.

  C.1. IF

> -> The Microsoft Excel IF function returns one value if the condition is TRUE, or another value if the condition is FALSE

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘐𝘍( 𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯, 𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘵𝘳𝘶𝘦, [𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘧𝘢𝘭𝘴𝘦] )
> ![IF](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/ab41a034-6afc-49be-9166-91fef2980a83)

  C.2. AND

> -> The Microsoft Excel AND function returns TRUE if all arguments evaluate TRUE else return FALSE.
 
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘈𝘕𝘋( 𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯1, [𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯2], ... )
> ![AND](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/2ef230d3-cbce-4dd0-b39e-f54d231327ed)

  C.3. OR

> -> The OR function in Excel returns TRUE if any of the conditions are true and returns FALSE if all conditions are false.
 
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘖𝘙( 𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯1, [𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯2, ... 𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯_𝘯] )
> ![OR](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/adcb0551-388c-4008-85ee-20a2e95c326e)

  C.4. NOT

> -> The Microsoft Excel NOT function is used to check if one value is not equal to another If we give TRUE, it will return FALSE, and when given FALSE, it will return TRUE.
 
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘕𝘖𝘛(𝘭𝘰𝘨𝘪𝘤𝘢𝘭)
> ![NOT](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/792b0647-8487-466a-b8fd-087687d558c9)

  C.5. XOR

> -> The XOR Function was introduced in Excel 2013 and is available under Excel Logical functions. It is a logical "exclusive OR" function.
>
> -> For two given logical statements, the XOR function would return TRUE if one of the statements is true and FALSE if both statements are true. If neither of the statements is true, it also returns FALSE.

𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘟𝘖𝘙( 𝘭𝘰𝘨𝘪𝘤𝘢𝘭1, [𝘭𝘰𝘨𝘪𝘤𝘢𝘭2], ... )
> ![XOR](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/a2241e27-4df3-4244-8789-e0090027a5fe)

  C.6. ISBLABK

> -> The Microsoft Excel IF function returns one value if the condition is TRUE, or another value if the condition is FALSE.
 
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘐𝘍( 𝘤𝘰𝘯𝘥𝘪𝘵𝘪𝘰𝘯, 𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘵𝘳𝘶𝘦, [𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘧𝘢𝘭𝘴𝘦] )
> ![ISBLANK](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/351376d3-5b55-4bd5-b574-a7d7f8d4856e)

  C.7. IFERROR

> -> The Microsoft Excel IFERROR function returns an alternate value if a formula results in an error.
>
> -> It will check for errors such as #N/A, #VALUE!, #REF!, #DIV/O!, #NUMI, #NAME? or #
 
𝑺𝒚𝒏𝒕𝒂𝒙

    =𝘐𝘍𝘌𝘙𝘙𝘖𝘙 (𝘷𝘢𝘭𝘶𝘦, 𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘦𝘳𝘳𝘰𝘳) 
> ![IFERROR](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/12a0b988-1905-4522-bbba-1b86d71e0a7f)

  C.8. IFNA

> -> The IFNA function in Excel returns an alternate value as specified by the user if a formula results in an #N/A error.
 
𝑺𝒚𝒏𝒕𝒂𝒙

    = 𝘐𝘍𝘕𝘈(𝘷𝘢𝘭𝘶𝘦, 𝘷𝘢𝘭𝘶𝘦_𝘪𝘧_𝘯𝘢)  
> ![IFNA](https://github.com/John-Rey-Decano/MX-4101-Group-5-Pratice-of-Text-Math-and-Logical-Functions/assets/143807174/6b3d038d-10b4-4969-a8a1-ac34d6fb2a5b)


