# String.h

-	void *memchr(const void *str, int c, size_t n)	Выполняет поиск первого вхождения символа c (беззнаковый тип) в первых n байтах строки, на которую указывает аргумент str.
  
-	int memcmp(const void *str1, const void *str2, size_t n)	Сравнивает первые n байтов str1 и str2.
  
-	void *memcpy(void *dest, const void *src, size_t n)	Копирует n символов из src в dest.
  
-	void *memset(void *str, int c, size_t n)	Копирует символ c (беззнаковый тип) в первые n символов строки, на которую указывает аргумент str.
  
-	char *strncat(char *dest, const char *src, size_t n)	Добавляет строку, на которую указывает src, в конец строки, на которую указывает dest, длиной до n символов.
  
-	char *strchr(const char *str, int c)	Выполняет поиск первого вхождения символа c (беззнаковый тип) в строке, на которую указывает аргумент str.
  
-	int strncmp(const char *str1, const char *str2, size_t n)	Сравнивает не более первых n байтов str1 и str2.
  
-	char *strncpy(char *dest, const char *src, size_t n)	Копирует до n символов из строки, на которую указывает src, в dest.
  
-	size_t strcspn(const char *str1, const char *str2)	Вычисляет длину начального сегмента str1, который полностью состоит из символов, не входящих в str2.
  
-	char *strerror(int errnum)	Выполняет поиск во внутреннем массиве номера ошибки errnum и возвращает указатель на строку с сообщением об ошибке. Нужно объявить макросы, содержащие массивы сообщений об ошибке для операционных систем mac и linux. Описания ошибок есть в оригинальной библиотеке. Проверка текущей ОС осуществляется с помощью директив.
  
-	size_t strlen(const char *str)	Вычисляет длину строки str, не включая завершающий нулевой символ.
  
-	char *strpbrk(const char *str1, const char *str2)	Находит первый символ в строке str1, который соответствует любому символу, указанному в str2.
  
-	char *strrchr(const char *str, int c)	Выполняет поиск последнего вхождения символа c (беззнаковый тип) в строке, на которую указывает аргумент str.

-	char *strstr(const char *haystack, const char *needle)	Находит первое вхождение всей строки needle (не включая завершающий нулевой символ), которая появляется в строке haystack.
  
-	char *strtok(char *str, const char *delim)	Разбивает строку str на ряд токенов, разделенных delim.
