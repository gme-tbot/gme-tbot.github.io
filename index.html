<?php
$fp = fopen('php.csv', 'a+b');
if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    fputcsv($fp, [$_POST['name'], $_POST['comment']]);
    rewind($fp);
}
while ($row = fgetcsv($fp)) {
    $rows[] = $row;
}
fclose($fp);
?>

<!DOCTYPE html>


<html lang="ja">
    <head>
        <meta charset="UTF-8">
        <title>掲示板</title>
        <link rel="stylesheet" type="text/css" href="keijiban.css">
    </head>
 
    <body>
        <h1>掲示板</h1>
        <section class="toukou">
            <h2>新規投稿</h2>
            <from action="#" method="POST">
                <div class="onamae">名前:<input type="text" name="name"><br></div>
                <div class="honbun1">本文:</div>
                <div class="honbun2"><textarea name="section" rows="3"></textarea><br></div>
                <button type="submit">送信する</button>
            </from>
        </section>
        <section class="itiran">
            <h2>投稿一覧</h2>

            <?php if (!empty($rows)): ?>
    <ul>
<?php foreach ($rows as $row): ?>
        <li><?php print $row[1];?> (<?php print $row[0];?>)</li>
<?php endforeach; ?>
    <ul>
 <?php else: ?>
            <p>投稿はまだありません</p>
        <?php endif; ?>
        </section>
    </body>    
</html>
