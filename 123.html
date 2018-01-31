<?
include("data/dd.php");
if($id>=0 && $id!=""){}else{ header("Location: blog.php"); }
if(!$nick || !$mess){
	$blog=ffile("data/blog/blog.dat");
	$use=explode("|", $blog[$id]);
	include("data/header.php");
	echo "$use[2]<br><i>Добавил $use[0] [$use[1]]</i><br><form action='write.php?id=$id' method=post><input type=text name=nick value='Ваше имя' size=30><br><textarea name=mess></textarea><br><input type=submit value=Post!></form>";
}else{
	if(strlen($nick)>$maxnick || strlen($mess)>$maxmess){
		die("<font color=red>Длина имени не должна превышать $maxnick символов. Длина сообщения не должна превышать $maxmess</font> / <a href=write.php?id=$id>еще раз</a>");
	include("data/footer.php");
	}elseif($nick==$elogin){
		if($clogin!=$elogin || $cpass!=$epass){
			die("<font color=red>Нельзя подписываться администратором, пока вы не вошли</font> / <a href='login.php>вход</a>");
		}
	}
	$nick=ktegs($nick);
	$mess=ktegs($mess);
	$f=fopen("data/blog/$id.dat", "a+");
	fwrite($f, "$nick|$mess\r\n");
	fclose($f);
	header("Location: post.php?id=$id");
}
?>
