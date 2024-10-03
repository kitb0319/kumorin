<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>개인용 노래들 링크</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: space-between; /* 왼쪽과 오른쪽 공간 배분 */
            height: 100vh;
            margin: 0;
            padding: 50px;
            background-image: url('https://ibb.co/tbZB9Dn'); /* 배경 이미지 경로 */
            background-size: cover; /* 배경 이미지 크기 조절 */
            background-position: center; /* 배경 이미지 위치 조정 */
        }

        @keyframes fade {
            0% {
                opacity: 0.5; /* 희미한 상태 */
            }
            100% {
                opacity: 1; /* 명확한 상태 */
            }
        }

        .button-container {
            display: flex;
            flex-direction: column; /* 세로 방향으로 나열 */
            margin-top: 20px; /* 버튼과 이미지 간 간격 */
            opacity: 0; /* 초기 상태 희미함 */
            animation: fade 0.5s forwards; /* 버튼 전체의 애니메이션 */
            animation-delay: 0.5s; /* 약간의 지연 */
        }
        
        .button {
            padding: 30px 60px;
            font-size: 48px;
            cursor: pointer;
            background-color: rgba(0, 123, 255, 0.8); /* 배경 색상과 투명도 */
            color: white;
            border: none;
            border-radius: 5px;
            margin-bottom: 30px; /* 버튼 간격 */
            text-align: center;
            text-decoration: none; /* 링크 텍스트 밑줄 제거 */
            opacity: 0; /* 초기 상태 희미함 */
            animation: slideFadeIn 1.5s forwards; /* 버튼 애니메이션 */
        }

        .button:nth-child(1) {
            animation-delay: 1.5s; /* 첫 번째 버튼 지연 시간 */
        }

        .button:nth-child(2) {
            animation-delay: 2.0s; /* 두 번째 버튼 지연 시간 */
        }

        .button:nth-child(3) {
            animation-delay: 2.5s; /* 세 번째 버튼 지연 시간 */
        }

.speech-bubble {
	position: relative;
	background: #c9f1fc;
	border-radius: .9em;
	width: 315px;
	column: 150px;
}

.speech-bubble:after {
	content: '';
	position: absolute;
	left: 0;
	top: 60%;
	width: 0;
	height: 0;
	border: 36px solid transparent;
	border-right-color: #c9f1fc;
	border-left: 0;
	border-bottom: 0;
	margin-top: -18px;
	margin-left: -36px;
}
        @keyframes slideFadeIn {
            0% {
                transform: translateY(-50px); /* 위에서 내려오는 효과 */
                opacity: 0; /* 초기 상태 희미함 */
            }
            100% {
                transform: translateY(0); /* 원래 위치로 */
                opacity: 1; /* 명확한 상태 */
            }
        }

        img {
            max-width: 600px; /* 이미지 최대 너비 설정 */
            height: auto; /* 자동 높이 조정 */
        }
    </style>
</head>
<body>
    <div class="button-container">
        <a href="https://youtube.com/playlist?list=PLvENEmzAemPwYscttWzwHLBWjNt9JAq2H&si=M1M1DqtBNMx3RxI7" class="button" target="_blank">노래추천</a>
        <a href="https://youtube.com/playlist?list=PLvENEmzAemPydt3o9vFhH6wLD8Ayqq6zN&si=nyZZgLHVF_XkRzYd" class="button" target="_blank">스텔라이브</a>
        <a href="https://youtube.com/playlist?list=PLvENEmzAemPwerqb50nDlPxmSpY8_069Y&si=Wyxlb5CCPQnmy403" class="button" target="_blank">청춘돼지</a>
    </div>
<div class="speech-bubble">
	<h1>"쿠리미들! 굿모린~!"</h1>
</div>
</body>
</html>
