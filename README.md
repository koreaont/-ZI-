<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🥵ZI존 하윤🥵</title>
    <script>
        let count = 0;  // 팝업 횟수 카운트
        const maxCount = 50;  // 최대 팝업 횟수 (50번)

        function showPopup() {
            if (count < maxCount) {
                count++;
                let progress = Math.floor((count / maxCount) * 100);  // 진행률 계산

                // 팝업 내용 설정
                let message = `😂😂그걸속냐 띨띨아🤣🤣\n${count}/50`;
                alert(message);

                // 50번까지 팝업을 띄우고 나서 리다이렉트
                if (count === maxCount) {
                    window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";  // 유튜브 링크로 리다이렉트
                } else {
                    showPopup();  // 계속해서 팝업을 띄운다
                }
            }
        }

        // 페이지 로드 시 팝업을 시작
        window.onload = function() {
            showPopup();
        };
    </script>
</head>
<body>
    <h1>BSM1129,PSH0125,CHY0125</h1>
    <p>ㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋ</p>
</body>
</html>
