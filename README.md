На вход программе подаётся английский текст, заканчивающийся точкой (символ «точка» во входных данных единственный). Текст зашифровать следующим образом: сначала определяется количество букв в самом длинном слове, обозначив полученное число К (словом называется непрерывная последовательность английских букв, слова друг от друга отделяются пробелами и запятыми, длина слова не превышает 20 символов). Затем проводится замена каж¬дой английской буквы на букву, следующую за ней К-ю по счету в алфавите (алфавит считается циклическим, то есть после буквы Z стоит буква А), оставив другие символы неизменными. Строчные буквы при этом остались строчными, а прописные - прописными. Требуется написать программу, которая будет выводить на экран зашифрованный текст и число К.