# Pr1_zad
<!DOCTYPE HTML>
 <html>
 <head> 
<title>Индивидуальное задание номер 810</title>
</head> 
<body> 
<form> 
 </form>
<script>   
            var q; 
            var w;
            var y;
            var r;
            var u;
            var j;
			var z;
			var n;
            var c = prompt('Введите число', '');
            var arr = new Array(4);
            if (c > 10)
            {    
                if (c < 100)
                {
                    j = 2;
                    q = c % 10;
                    w = c/10;
					w = parseInt(w);
                    arr[0] = w;
                    arr[1] = q;
                }
                else
                {
                    j = 3;
                    q = c % 100;
                    w = c/100;
					w = parseInt(w);
                    r = q % 10;
                    u = q/10;
					u = parseInt(u);
                    arr[0] = w;
                    arr[1] = u;
                    arr[2] = r;
                }
            }
            else
            {
                j = 1;
                arr[0] = c;
            }
            if (c == 1000) alert("Тысяча");
            if (j == 1)
            {
                if (arr[0] == 1) y = "Один";
                if (arr[0] == 2) y = "Два";
                if (arr[0] == 3) y = "Три";
                if (arr[0] == 4) y = "Четыре";
                if (arr[0] == 5) y = "Пять";
                if (arr[0] == 6) y = "Шесть";
                if (arr[0] == 7) y = "Семь";
                if (arr[0] == 8) y = "Восемь";
                if (arr[0] == 9) y = "Девять";
                alert (y);
            }

            else if (j == 2)
            {   
			    if(arr[0]== 1)
				{
				if (arr[1] == 1) y = "Одинадцать";
                if (arr[1] == 2) y = "Двенадцать";
                if (arr[1] == 3) y = "Тринадцать";
                if (arr[1] == 4) y = "Четырнадцать";
                if (arr[1] == 5) y = "Пятнадцать";
                if (arr[1] == 6) y = "Шестнадцать";
                if (arr[1] == 7) y = "Семнадцать";
                if (arr[1] == 8) y = "Восемьнадцать";
                if (arr[1] == 9) y = "Девятнадцать";
				}
                if (arr[0] == 2) z = "Двадцать";
                if (arr[0] == 3) z = "Тритцать";
                if (arr[0] == 4) z = "Сорок";
                if (arr[0] == 5) z = "Пятьдесят";
                if (arr[0] == 6) z = "Шестьдесят";
                if (arr[0] == 7) z = "Семьдесят";
                if (arr[0] == 8) z = "Восемьдесят";
                if (arr[0] == 9) z = "Девяносто";
				if( arr[0] != 1)
				{
                if (arr[1] == 1) y = "один";
                if (arr[1] == 2) y = "два";
                if (arr[1] == 3) y = "три";
                if (arr[1] == 4) y = "четыре";
                if (arr[1] == 5) y = "пять";
                if (arr[1] == 6) y = "шесть";
                if (arr[1] == 7) y = "семь";
                if (arr[1] == 8) y = "восемь";
                if (arr[1] == 9) y = "девять";
				}
               if (arr[0]!= 1) alert (z+" "+y);
			   else if (arr[0] == 1) alert (y);
            }
          		  else if (j == 3)
            {
                if (arr[0] == 1) y = "Сто";
                if (arr[0] == 2) y = "Двести";
                if (arr[0] == 3) y = "Триста";
                if (arr[0] == 4) y = "Четыреста";
                if (arr[0] == 5) y = "Пятьсот";
                if (arr[0] == 6) y = "Шестьсот";
                if (arr[0] == 7) y = "Семьсот";
                if (arr[0] == 8) y = "Восемьсот";
                if (arr[0] == 9) y = "Девятьсот";
				if(arr[1]== 1)
				{
				if (arr[2] == 1) z = "Одинадцать";
                if (arr[2] == 2) z = "Двенадцать";
                if (arr[2] == 3) z = "Тринадцать";
                if (arr[2] == 4) z = "Четырнадцать";
                if (arr[2] == 5) z = "Пятнадцать";
                if (arr[2] == 6) z = "Шестнадцать";
                if (arr[2] == 7) z = "Семнадцать";
                if (arr[2] == 8) z = "Восемьнадцать";
                if (arr[2] == 9) z = "Девятнадцать";
				}
                if (arr[1] == 2) z = "Двадцать";
                if (arr[1] == 3) z = "Тритцать";
                if (arr[1] == 4) z = "Сорок";
                if (arr[1] == 5) z = "Пятьдесят";
                if (arr[1] == 6) z = "Шестьдесят";
                if (arr[1] == 7) z = "Семьдесят";
                if (arr[1] == 8) z = "Восемьдесят";
                if (arr[1] == 9) z = "Девяносто";
				if (arr[1]!= 1)
				{
                if (arr[2] == 1) n = "Один";
                if (arr[2] == 2) n = "Два";
                if (arr[2] == 3) n = "Три";
                if (arr[2] == 4) n = "Четыре";
                if (arr[2] == 5) n = "Пять";
                if (arr[2] == 6) n = "Шесть";
                if (arr[2] == 7) n = "Семь";
                if (arr[2] == 8) n = "Восемь";
                if (arr[2] == 9) n = "Девять";
				}
				if( arr[1] == 1) alert (y + " "+ z );
				else  if (arr[1]!= 1)alert (y + " "+ z + " " + n);
            }
            else if (c == 1000) alert("Тысяча");
</script>
<p> Задание номер 810 </p>
Дано натуральное число n(n<=1000). Напечатать это число русскими словами(например: двести сорок один).
 </body>
 </html> 
