примеры ошибок с ветками 

* ошибки слияния наложение строк друг на друга

пример: 
<<<<<<< HEAD
>error_error_error_error_error_error
>>**error_error_error_error_error**
>>>~~error_error_error_error~~
>error_error_error_error_error_error
>>**error_error_error_error_error**
>>>~~error_error_error_error~~
>error_error_error_error_error_error
>>**error_error_error_error_error**
>>>~~error_error_error_error~~
=======
* ~~error_error_error~~
> text
* _error_error_
> text
* 
> text
>>>>>>> error1
*
__error_error___
> text
* _error_error
> text