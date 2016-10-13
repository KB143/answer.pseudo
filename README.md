# answer.pseudo
//function that accepts parameter in laravel

public function showResult($name)
{
  $rand_no = rand(6 , 11);
  echo"Name GeneratedNumber:".$name.$rand_no;
}

