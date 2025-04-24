<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <title>PHP ilə Dinamik Səhifə</title>
</head>
<body>
    <?php
        // PHP elementləri: dəyişənlər
        $ad = "Əli";
        $yas = 25;

        // PHP ifadəsi və operatorlar
        $kecid = ($yas >= 18) ? "Böyüksən" : "Hələ kiçiksən";

        // PHP funksiyası
        function salamla($ad) {
            return "Salam, $ad!";
        }

        echo "<h1>" . salamla($ad) . "</h1>";
        echo "<p>Yaşınız: $yas</p>";
        echo "<p>Status: $kecid</p>";

        // Dəyişən artımı (operator)
        $yas++;
        echo "<p>Gələn il yaşınız: $yas</p>";
    ?>
</body>
</html>
