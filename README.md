# 7laba
<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №7 <br>
по предмету «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script, PHP"</b><p>
<p align="right"><b>Выполнил: </b> студент 331 группы Хорошко Илья Алексеевич</p>
<p  align="right"><b>Проверил: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2024</p>
<h2> Введение </h2>
<p align="justify">Решение задач на js с помощью Node.js , написание скрипта для парсинка данных, создание Qr-кода и создание скрипта для отправки писем на почту. </p>
<h2 align="center">Цели и задачи</h2>

1.  Создайте переменную $var и присвойте ей значение 'hello'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'e', символ 'o'.
2.	Напишите скрипт, который считает количество секунд в часе.
3.	Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки:
```php
<?php
	$var = 1;
	$var = $var + 12;
	$var = $var - 14;
	$var = $var * 5;
	$var = $var / 7;
	$var = $var + 1;
	$var = $var - 1;
	echo $var;
?>
```
4.	 Создайте переменную `$a` и присвойте ей значение 3. Выведите значение этой переменной на экран.
5.	Создайте переменные `$a=10` и `$b=2`. Выведите на экран их сумму, разность, произведение и частное (результат деления).
6.	Создайте переменные `$c=15` и `$d=2`. Просуммируйте их, а результат присвойте переменной `$result`. Выведите на экран значение переменной `$result`.
7.	Создайте переменные `$a=10`, `$b=2` и `$c=5`. Выведите на экран их сумму.
8.	 Создайте переменные `$a=17` и `$b=10`. Отнимите от `$a` переменную `$b` и результат присвойте переменной `$c`. Затем создайте переменную `$d`, присвойте ей значение 7. Сложите переменные `$c` и `$d`, а результат запишите в переменную `$result`. Выведите на экран значение переменной `$result`.
9.	Создайте переменную `$text` и присвойте ей значение `'Привет, Мир!'`. Выведите значение этой переменной на экран.
10.	 Создайте переменные `$text1='Привет, '` и `$text2='Мир!'`. С помощью этих переменных и операции сложения строк выведите на экран фразу `'Привет, Мир!'`.
11.	 Создайте переменную `$name` и присвойте ей ваше имя. Выведите на экран фразу `'Привет, %Имя%!'`. Вместо `%Имя%` должно стоять ваше имя.
12.	 Создайте переменную `$age` и присвойте ей ваш возраст. Выведите на экран `'Мне %Возраст% лет!'`.
13.	Создайте переменную `$text` и присвойте ей значение `'abcde'`. Обращаясь к отдельным символам этой строки выведите на экран символ 'a', символ 'c', символ 'e'.
14.	 Дана произвольная строка, например, 'abcde'. Поменяйте первую букву (то есть букву 'a') этой строки на '!'.
15.	 Создайте переменную `$num` и присвойте ей значение '12345'. Найдите сумму цифр этого числа.
16.	Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.
17.	 Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.
18.	 Создайте переменную, присвойте ей число. Возведите это число в квадрат (это значит нужно умножить его само на себя). Выведите его на экран.
19.	Переделайте этот код так, чтобы в нем использовались операции +=, -=, *=, /=. Количество строк кода при этом не должно измениться.
```php
$var = 47;
$var = $var + 7;
$var = $var - 18;
$var = $var * 10;
$var = $var / 20;
echo $var;
```
20.	 Переделайте этот код так, чтобы в нем использовалась операция .=. Количество строк кода при этом не должно измениться.
```php
$text = 'Я';
$text = $text.' хочу';
$text = $text.' знать';
$text = $text.' PHP!';
echo $text;
```
21.	 Переделайте этот код так, чтобы в нем использовались операции ++ и --. Количество строк кода при этом не должно измениться.
```php
$var = 10;
$var = $var + 1;
$var = $var + 1;
$var = $var - 1;
echo $var;
```
22.	 Переделайте этот код так, чтобы в нем использовались операции ++, -- , +=, -=, *=, /=. Количество строк кода при этом не должно измениться.
```php
$var = 10;
$var = $var + 7;
$var = $var + 1;
$var = $var - 1;
$var = $var + 12;
$var = $var * 7;
$var = $var - 15;
echo $var;
```

### CodeWars
* https://www.codewars.com/kata/534ea96ebb17181947000ada
* https://www.codewars.com/kata/5552101f47fc5178b1000050
* https://www.codewars.com/kata/52988f3f7edba9839c00037d
* https://www.codewars.com/kata/5506b230a11c0aeab3000c1f
* https://www.codewars.com/kata/57bf599f102a39bb1e000ae5
* https://www.codewars.com/kata/5901f361927288d961000013
* https://www.codewars.com/kata/546f922b54af40e1e90001da
* https://www.codewars.com/kata/5679aa472b8f57fb8c000047
* https://www.codewars.com/kata/57a2013acf1fa5bfc4000921
* https://www.codewars.com/kata/5a995c2aba1bb57f660001fd
* https://www.codewars.com/kata/57ed30dde7728215300005fa
* https://www.codewars.com/kata/582746fa14b3892727000c4f
* https://www.codewars.com/kata/5b39e3772ae7545f650000fc



<h2 align="center">Решение задач</h2>

```php
<h4>Задание 1: </h4>
<?php
$var = "hello";
echo $var[0];
echo $var[1];
echo $var[4];
?>


<h4>Задание 2: </h4>
<?php
$sec = 60*60;
echo "В часе $sec секунд"
?>


<h4>Задание 3: </h4>
<?php
	$var = 1;
	$var += 12;
	$var -= 14;
	$var *= 5;
	$var /= 7;
	$var += 1;
	$var -= 1;
	echo $var;
?>


<h4>Задание 4: </h4>
<?php
	$a = 3;
	echo "Значение переменной \$a равно $a";
?>


<h4>Задание 5: </h4>
<?php
	$a = 10;
	$b = 2;
	$c = $a+$b;
	echo "\$a+\$b = $c <br>";
	$c = $a-$b;
	echo "\$a-\$b = $c <br>";
	$c = $a*$b;
	echo "\$a*\$b = $c <br>";
	$c = $a/$b;
	echo "\$a/\$b = $c <br>";
?>


<h4>Задание 6: </h4>
<?php
	$a = 10;
	$b = 2;
	$c = 5;
	$result = $a+$b+$c;
	echo "\$a+\$b+\$c = $result";
?>


<h4>Задание 7: </h4>
<?php
	$a = 17;
	$b = 10;
	$c = $a-$b;
	$d = 7;
	$result = $c+$d;
	echo "\$result = $result";
?>


<h4>Задание 8: </h4>
<?php
	$a = 'Привет, Мир!';
	echo $a;
?>



<h4>Задание 9: </h4>
<?php
	$text1 = 'Привет, '; 
	$text2 = 'Мир!'; 
	echo $text1 . $text2;
?>


<h4>Задания 10,11: </h4>
<?php
	$name = 'Сергей'; 
	$age = '19'; 
	echo "Привет, $name <br>";
	echo "Мне $age лет!";
?>

<h4>Задание 12: </h4>
<?php
	$text = 'abcde';  
	echo $text[0] . $text[2] . $text[4];
?>



<h4>Задание 13: </h4>
<?php
	$text = 'abcde';  
	$text[0] = '!';
	echo "Вот измененная строка $text";
?>


<h4>Задание 14: </h4>
<?php
	$num = 12345;
	$sum = 0;
    while($num!=0)
	{
		$sum+=$num%10;
		$num = $num/10;
	}	
	echo "Сумма цифр числа 12345 равна $sum";
?>


			
<h4>Задание 15: </h4>
<?php
	echo "В часе " . 60*60 . " секунд <br>";
	echo "В сутках " . 60*60*24 . " секунд <br>";
	echo "В месяцe " . 60*60*24*30 . " секунд <br>";
?>


<h4>Задание 16: </h4>
	<?php
	$hour = 60 * 60;
	echo $hour . ' Секунд в часе! ';
	$day = $hour * 24;
	echo $day . ' Секунд в дне! ';
	$month = $day * 30;
	echo $month . ' Секунд в месяце! ';
	?>


<h4>Задание 17: </h4>
<?php
	date_default_timezone_set('Asia/Sakhalin');
	echo date('h:i:s a', time());
?>


<h4>Задание 18: </h4>
<?php
	$num = 7;
	echo "Это число $num <br>";
	$num*=$num;
	echo  "Это его квадрат: $num"
?>		


<h4>Задание 19: </h4>
<?php
$var = 47;
$var += 7;
$var -= 18;
$var *= 10;
$var /= 20;
echo $var;

?>


<h4>Задание 20: </h4>
<?php
$text = 'Я';
$text .=' хочу';
$text .=' знать';
$text .=' PHP!';
echo $text;
?>


<h4>Задание 21: </h4>
<?php
$var = 10;
$var++;
$var++;
$var--;
echo $var;
?>


<h4>Задание 22: </h4>
<?php
$var = 10;
$var +=7;
$var++;
$var--;
$var +=12;
$var *=7;
$var -=15;
echo $var;
?>

```
### CodeWars

1. 
```javascript
function breakChocolate(n,m) {
  
  return (n * m === 0) ? 0 : n * m - 1;
}
```

2. 
```javascript
function digPow(n, p){
  let sum = 0;
  for(let i = 0, j = p; i < n.toString().length; i++, j++){
    sum += Math.pow(parseInt(n.toString()[i]), j);
  }
  
  return sum % n == 0 ? sum / n : -1;

}
```
3. 
```javascript
function reject(array, predicate) {
  let result = [];
  for(let i in array){
    if(!predicate(array[i])) result.push(array[i]);
  }
  return result;
}
```
4. 
```javascript
function evaporator(content, evap_per_day, threshold){ 
  let days = 0;
  threshold = threshold * 0.01 * content
  
  while(content >= threshold){
    content *= ((100 - evap_per_day) * 0.01);
    days++;
  }
  return days;
}
```
5. 
```javascript
var fibsFizzBuzz = function(n) {
    let array = [];
    for(let i = 0; i < n; i++){
      if (i == 0 || i == 1) {
        array.push(1);
      }
      else {
        array.push(array[i - 2] + array[i - 1]);
      }
    }
    for(let i = 0; i < n; i++)
    {
        if(array[i] % 3 == 0 & array[i] % 5 == 0) array[i] = 'FizzBuzz';
        if(array[i] % 3 == 0) array[i] = 'Fizz';
        if(array[i] % 5 == 0) array[i] = 'Buzz';
    }
    return array;
  }
```
6. 
```javascript
function product(values) {
  let mp = 1;
  for(let i in values){
    mp *= values[i];
  }
  return values == null || values.length == 0 ? null : mp;
}
```
7. 
```javascript
function alphabetPosition(text) {
  let result = "";
  for (let i = 0; i < text.length; i++){
    let code = text.toUpperCase().charCodeAt(i)
    if (code > 64 && code < 91) result += (code - 64) + " ";
  }

  return result.slice(0, result.length-1);
}
```
8. 
```javascript
function findEvenIndex(arr)
{
  for(let i = 0; i < arr.length; i++){
    let sum1 = 0;
    for(let j = 0; j < i; j++){
      sum1 += arr[j];
    }
    
    let sum2 = 0;
    for(let j = i + 1; j < arr.length; j++){
      sum2 += arr[j];
    }
    
    if(sum1 == sum2) return i;
  }
  
  return -1;
}
```
9. 
```javascript
function findAverage(array) {
  let avarage = 0;
  for(let i in array)
    avarage += array[i];
  return array.length == 0 ? 0 : avarage / array.length;
}
```
10. 
```javascript
function scrollingText(text){
  text = text.toUpperCase();
  let array = [text];
  for(let i = 0; i < text.length - 1; i++){
    let texttemp = text.split("");
    texttemp.push(texttemp.shift());
    text = texttemp.join("");
    array.push(text);
  }
  return array;
}
```
11. 
```javascript
function bump(str){
  let sum = 0;
  let array = str.split("");
  for(let i in array){
    if(array[i] == "n") sum++;
    if(sum > 15) return "Car Dead";
  }
  return "Woohoo!";
}
```
12. 
```javascript
function countDevelopers(list) {
  let count = 0;
  for(let i in list)
    if(list[i].continent === 'Europe' && list[i].language === 'JavaScript') count++;
  return count;
}
```

13. 
```javascript
function removeDuplicateWords (s) {
  let array = s.split(" ");
  let result = [];
  for(let i in array){
    if(result.indexOf(array[i]) == -1)
      result.push(array[i]);
  }
  return result.join(" ");
}
```

### QR-код

```javascript
app.get("/qrcode", async function(req, resp){
    const url = req.query.url;
  
    if (!url) {
      return resp.status(400).send('ссылка для создания не указана, у тебя лапки !');
    }
  
    try {
      const qr = await QRCode.toDataURL(url);
      resp.send(`<img src="${qr}" />`);
    } catch (err) {
      resp.status(500).send('Ошибка, у вас лапки вместо рук');
    }
});

```
### Отправка email

```javascript
const smtpConfig = {
  host: 'smtp.mail.ru',
  port: 587,
  secure: false, // true для SSL, false для других
  auth: {
    user: 'khoroshko12@mail.ru',
    pass: 'J58jAC5MDSLFji4rZJMq',
  },
};

//  для отправки почты
const transporter = nodemailer.createTransport(smtpConfig);

// Параметры 
const mailOptions = {
  from: 'khoroshko12@mail.ru',
  to: 'khoroshko4@mail.ru',
  subject: 'Тема письма',
  text: 'Какой-то текст с котиками ฅ^•ﻌ•^ฅ',
 
};

// Отправляем 
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    return console.log('Ошибка отправки письма:', error);
  }
  console.log('Письмо успешно отправлено:', info.messageId);
});

```

### Парсинг

```javascript
app.get("/parse", async function(req, resp){
    const url = req.query.url;
    
    const response = await axios.get(url); 
    const res = response.data.match(/<span class=\"text-bold color-fg-default\">(.*)<\/span>/g);
    const str = "<span class=\"p-nickname vcard-username d-block\" itemprop=\"additionalName\">";
    let name = "";
    let i = response.data.indexOf(str) + str.length + 1;
    while(response.data[i] != '<'){
        name += response.data[i];
        i++;
    }
    name = name.trim();
    const followers = res[0].substring(res[0].indexOf(">") + 1, res[0].lastIndexOf("<"));
    const following = res[1].substring(res[1].indexOf(">") + 1, res[1].lastIndexOf("<"));
    
    const result = {
        никнейм_на_гитхабе: name,
        подписчики: followers,
        подписки: following,
    };
    resp.send(result);

    if(!fs.existsSync("БД_ФАЙЛ.txt")){
        fs.open('БД_ФАЙЛ.txt', 'w', (err) => {
            if(err) throw err;
            console.log('Файл с бд успешно создан!');
        }); 
    }
    fs.appendFileSync('БД_ФАЙЛ.txt', `Никнейм на гитхабе : ${result.name} ( коллличество подписчиков: ${result.followers} )  кол-во подписок: ${result.following}\n`, (err)=>{
        if(err) throw err;
        console.log("Данные успешно записаны");
    });
});

app.listen(3000, function(req, resp){
    console.log("Server online.")

});

```
<h2 align="center">Вывод</h2>
В ходе работы изучил как создавать QR-код при помощи Node Js, как сделать скрипты для парсинга данных с сайта и переместить их в файл, также как отправлять почту и вспомнил некоторые моменты в PHP
